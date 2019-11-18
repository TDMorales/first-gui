# first-gui
my first gui

from tkinter import *
from tkinter import messagebox

class myguiApp:
    
    def __init__(self):
        window = Tk()
        window.title("My GUI App")
        label = Label(window,text="This is a processing Event and Functions Created")
        btnOK = Button(window,text="OK", fg="blue", bg="red", command = self.processEventOK)
        label_name = Label(window,text="What is your name ?")
        self.name = StringVar()
        entry_name = Entry(window,textvariable=self.name)
        btnCancel = Button(window, text="Cancel", fg="red", command = self.processEventCancel)
        label.pack()
        label_name.pack()
        entry_name.pack()
        btnOK.pack()
        btnCancel.pack()
        #window.mainloop()

    def processEventOK(self):
        print("OK Pressed !!!")
        messagebox.showinfo('Info Box','Welcome to GUI '+self.name.get())
    def processEventCancel(self):
        print("Cancel Button Pressed !!!")
