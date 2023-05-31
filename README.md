  # Втора лабораториска вежба по Софтверско инженерство
  Калина Спасева, бр на индекс. 213043

# Control Flow Graph
![image](https://github.com/kalinaspaseva/SI_2023_lab2_213043/assets/109042398/472ac406-86cc-483c-b41e-da0aaadf44d9)

# Цикломатска комплексност
Цикломатската комплексност на дадениот код е 11. Ја пресметав така што го избројав бројот на региони во графот, а за да 
го потврдам решението го пресметав и според формулата E-N+2 = 35-26+2 = 11

# Tест случаи според Every Branch критериумот
![image](https://github.com/kalinaspaseva/SI_2023_lab2_213043/assets/109042398/22183666-f8da-4a74-b964-bf1e5cc7b590)

# Тест случаи според Multiple Condition критериумот
Можни тест случаеви се:
T X X --> Ако user==null, другите два услови не се проверуваат
F T X --> Ако user!=null, user.getPassword()==null, третиот услов не се проверува
F F T --> Ако user!=null, user.getPassword()!=null, user.getEmail()==null (Третиот услов се исполнува)
F F F --> Ако user!=null, user.getPassword()!=null, user.getEmail()!=null (Условот не е исполнет)


