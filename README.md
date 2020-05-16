# Теория систем и системный анализ  
##Задача №1
### Вариант 3

Мебельная фабрика выпускает столы, стулья, бюро и книжные шкафы. При изготовлении этих товаров используются два различных типа досок. Кроме того, ресурсами являются трудовые затраты – количество рабочего времени, который требуется для создания единицы продукции (чел.-час.). Процесс производства ограничен максимальным размером используемых материальных и трудовых ресурсов.
В текстовом файле следует определить исходные данные задачи:
1) Максимальные размеры ресурсов;
2) Нормативы затрат каждого из видов ресурсов (материальных и трудовых) в расчете на изготовление единицы продукции;
3) Цены на продукцию.  

Построить математическую модель определения ассортимента выпускаемой продукции таким образом, чтобы общая прибыль фабрики была максимальной.
Написать программу, которая:
1) Решает задачу на основе данных из файла;
2) Проводит анализ на чувствительность при изменении максимальных ограничений на трудовые ресурсы (следует предложить изменения, которые не повлекут изменения плана выпуска продукции, и изменения, которые приведут к другому оптимуму).

___  
data:
1) data_table.csv - Информация о разновидности сырья. Запасы и затраты на единицу продукта.
2) prices.csv - Информация о ценах за единицу продукта
3) simplex_optimize_task.ipynb - код программы  
___
___
## Задача №2
### Вариант 3
Имеется задача нелинейного программирования  
<img src="http://www.sciweavers.org/tex2img.php?eq=x%5E2_1%20%2B%203x%5E2_2%20-%203x_1x_2%20%2B%20x_1%20-%206x_2%20%5Cxrightarrow%7B%7D%20min&bc=White&fc=Black&im=png&fs=24&ff=arev&edit=0" align="center" border="0" alt="x^2_1 + 3x^2_2 - 3x_1x_2 + x_1 - 6x_2 \xrightarrow{} min" width="592" height="50" />  

<img src="http://www.sciweavers.org/tex2img.php?eq=%5Cbegin%7Bcases%7D%204x_1%20%2B%203x_2%20%5Cleq%2012%20%5C%5C%20-x_1%20%2B%20x_2%20%5Cleq%201%20%5C%5C%20x_1%20%5Cgeq%200%20%5C%5C%20x_2%20%5Cgeq%200%20%5Cend%7Bcases%7D&bc=White&fc=Black&im=png&fs=24&ff=arev&edit=0" align="center" border="0" alt="\begin{cases} 4x_1 + 3x_2 \leq 12 \\ -x_1 + x_2 \leq 1 \\ x_1 \geq 0 \\ x_2 \geq 0 \end{cases}" width="286" height="186" />  

Необходимо:
1) Решить задачу безусловной минимизации градиентными методами
2) Решить задачу условной минимизации градиентными методами
3) Решить задачу с помощью метода условного градиента, без использования сторонних библиотек 
___  
data:  
1) nonlinear_programming_task.ipynb - Решение задач 1 и 2.
2) conditional_gradient_method.ipynb - Решение задачи №3  
