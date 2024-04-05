# first-project
from PyQt5.QtCore import Qt
from PyQt5.QtWidgets import QApplication, QWidget, QPushButton, QLabel, QVBoxLayout

app = QApplication([])
main_win = QWidget()
main_win.show()
main_win.setWindowTitle('Моё первое приложение')
Hello = QLabel('Hello, world!')
Hello.text()
v_line = QVBoxLayout()
v_line.addWidget(Hello, alignment = Qt.AlignCenter)
main_win.setLayout(v_line)

app.exec_()
