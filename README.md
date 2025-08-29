"""
README: Great Hub
Funções: Voar, andar na parede, pular alto
"""
from tkinter import *
root=Tk();root.title("Great Hub");Frame(root,width=200,height=150).pack()
Button(root,text="Voar").pack();Button(root,text="Andar na parede").pack();Button(root,text="Pular alto").pack()
root.mainloop()
