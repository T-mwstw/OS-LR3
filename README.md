# OS-LR3

Разработать программу для Windows, которая должна запускаться
в двух экземплярах - каждый в своем окне командной оболочки FAR или из
ПРОВОДНИКа операционной системы. Программа использует заранее подготовленный текстовый файл. Она пытается открыть этот файл для чтения с указываемым при этом запрете для других использовать этот файл. По результатам
выполнения системной функции открытия на экран выдается сообщение - удалось ли открыть файл и, если не удалось по причине отсутствия доступа к одновременно выполняемым программам, то сообщение именно об этой причине.
При отсутствии указанного в программе файла после сообщения об этом отсутствии программа прекращает работу. При его наличии, но невозможности продолжения действий из-за блокировки, установленной другим экземпляром
запущенной программы, выполняется ожидание освобождения файла от блокировки. При отсутствии указанной причины доступа программа должна ждать
освобождения файла. В обоих случаях - ожидания освобождения или исходной
доступности - программа читает из этого файла все находящиеся в нем данные
и выводит их на экран. Сообщения должны выводиться цветные и в середине
консольного окна
