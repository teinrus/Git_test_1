
# Работа класса SalesManager
=======

<li>Создание переменной:</li>
<ol>
    <li> Необходимо создать переменную типа <strong>SalesManager</strong> </li>


            SalesManager unit_1= new SalesManager();

  <li>В параметр мы передаем массив типа <strong>int</strong> </li>


            (new int[]{})

  <li>И заполняем массив значениями </li>


            {150,120,180}

  <li>В итоге получаем </li>


            SalesManager unit_1= new SalesManager(new int[]{150,120,180});

</ol>
<li>Метод: <strong>max</strong></li>
<ol>
<li>Как мы видим из кода это метод определения максимального значения </li>

    public int max() {
        int max = -1;
        for (int sale : sales) {
            if (sale > max) {
                max = sale;
            }
        }
        return max;
    }
<li>Для того чтобы его использовать нам необходимо вызвать данный метод </li>
            
    unit_1.max()

<li>И сразу выведим его на печать </li>

    System.out.println(unit_1.max());

</ol>



Для скачивания проекта перейди по [ссыллке](https://github.com/teinrus/Git_test_1.git)


