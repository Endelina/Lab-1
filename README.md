group: Предприятия  

Company = {
c_number:number, c_name:string,  rating:number, c_city:string
180, 'Electronics', 230,   'Gomel' 
230, 'Technoworld', 300,   'Moscow'
150, 'Appliances',   140, 'Gomel'
190, 'Master' ,  300,  'Minsk'
270, 'Stroymarker', 240, 'Moscow'
}

Products = { p_number:number, p_name:string, p_price:number, p_city:string
10, 'Microwave', 400, 'Gomel'
20, 'Dishwasher'  , 1000, 'Moscow'
30, 'Dryer'   , 650, 'Gomel'
40, 'Fridge'   , 800, 'Mogilev'
50, 'Washing machine'    , 700, 'Gomel'
60, 'Electric stove'   , 720, 'Moscow'
}

Worker = { w_number:number, w_name:string, w_city:string, birth:date, c_number:number 
55, 'Ivanov', 'Gomel', 1998-03-15, 180 
10, 'Petrov'  ,'Moscow', 1995-02-17, 230 
100, 'Sidorov'   , 'Gomel', 1993-12-03, 150
190, 'Ivanov'   , 'Mogilev', 1991-04-18, 190
130, 'Antonov'    , 'Mogilev', 1994-03-14, 190
90, 'Sergeev'   , 'Moscow', 1976-12-01, 180
}

Production =
{ c_number:number, p_number:number, year:number, number:number  
150, 30, 2016, 150
180, 10, 2016, 100
180, 60, 2018, 90
190, 50, 2015, 50
270, 50, 2016, 120
270, 20, 2016, 50
180, 20, 2017, 50
270, 40, 2017, 200
150, 10, 2016, 100
270, 30, 2017, 130
270, 10, 2017, 70
270, 60, 2018, 210
}
