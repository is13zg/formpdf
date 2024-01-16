#  create_pdf(directory, width, height, output_path='.', file_name='create_pdf', separation=1, margin=5)
#
# формирует pdf по заданной ширине и высоте картинки с разделительной сеткой, из папки с картинками
#
#  directory - путь до папки с картинками
#  width, height -  ширина и высота картинок на листе а4
#  output_path  -  путь куда сохранить полученный pdf, по умолчанию текущая папка откуда запускается скрипт
#  file_name  -  название конечного pdf файла, по умолчанию create_pdf
#  separation - толщина разделительной сетки, по умолчанию 1 мм
#  margin  -  отсуп от края листа, т.к. принтер не печатает с краев,  по умолчанию 5 мм
#
# Пример использования
# image_files = ['image1.png', 'image2.png', 'image3.png']
# create_pdf(image_files, 50, 50)
