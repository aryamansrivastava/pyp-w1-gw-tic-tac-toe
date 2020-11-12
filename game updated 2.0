from tkinter import *
import tkinter.messagebox

root = Tk()
root.geometry("1350x750+0+0")
root.title("TIC TAC TOE")
root.configure(background="cadet blue")
root.resizable(0,0)

Tops = Frame(root,bg="cadet blue",pady=2,width=1350,height=100,relief=RIDGE)
Tops.grid(row=0,column=0)
lblTitle = Label(Tops,font=("courier",50,"bold"),text="TIC-TAC-TOE GAME",bd=21,bg="cadet blue",fg="white",justify=CENTER)
lblTitle.grid(row=0,column=0)
MainFrame = Frame(root,bg="powder blue",pady=2,width=1350,height=100,relief=RIDGE,bd=10)
MainFrame.grid(row=1,column=0)
Bottom = Frame(MainFrame,bg="powder blue",pady=2,width=1350,height=50,relief=RIDGE)
Bottom.pack(side=BOTTOM)
lblAk = Label(Bottom,font=("courier",30,"bold"),text="MADE BY AAKAR GUPTA",bg="powder blue",fg="black",justify=CENTER)
lblAk.grid(row=0,column=0)

LeftFrame = Frame(MainFrame,bg="cadet blue",pady=2,width=750,height=524,relief=RIDGE,bd=10)
LeftFrame.pack(side=LEFT)
RightFrame = Frame(MainFrame,bg="cadet blue",pady=2,width=560,height=500,relief=RIDGE,bd=10)
RightFrame.pack(side=RIGHT)
RightFrame1 = Frame(RightFrame,bg="cadet blue",pady=2,width=560,height=250,relief=RIDGE,bd=10)
RightFrame1.grid(row=0,column=0)
RightFrame1a = Frame(RightFrame1,bg="powder blue",pady=2,width=560,height=250,relief=RIDGE,bd=5)
RightFrame1a.pack(side=TOP)
RightFrame1b = Frame(RightFrame1,bg="powder blue",pady=2,width=560,height=250,relief=RIDGE,bd=5)
RightFrame1b.pack(side=BOTTOM)
RightFrame2 = Frame(RightFrame,bg="cadet blue",pady=2,width=560,height=250,relief=RIDGE,bd=10)
RightFrame2.grid(row=1,column=0)

PlayerX = IntVar()
PlayerO = IntVar()
PlayerX.set(0)
PlayerO.set(0)

buttons = StringVar()
click = True
def checker(buttons):
    global click
    if(buttons["text"]==" " and click==True):
        buttons["text"]="X"
        click = False
        scorekeeper()
    elif(buttons["text"]==" " and click==False):
        buttons["text"]="O"
        click = True
        scorekeeper()
def scorekeeper():
    if(button1["text"]=="X" and button2["text"]=="X" and button3["text"]=="X"):
        button1.configure(background="sky blue")
        button2.configure(background="sky blue")
        button3.configure(background="sky blue")
        n = int(PlayerX.get())
        score = n + 1
        PlayerX.set(score)
        tkinter.messagebox.showinfo("WINNER X","YOU HAVE JUST WON A GAME!")
        reset()
    if(button4["text"]=="X" and button5["text"]=="X" and button6["text"]=="X"):
        button4.configure(background="sky blue")
        button5.configure(background="sky blue")
        button6.configure(background="sky blue")
        n = int(PlayerX.get())
        score = n + 1
        PlayerX.set(score)
        tkinter.messagebox.showinfo("WINNER X","YOU HAVE JUST WON A GAME!")
        reset()
    if(button7["text"]=="X" and button8["text"]=="X" and button9["text"]=="X"):
        button7.configure(background="sky blue")
        button8.configure(background="sky blue")
        button9.configure(background="sky blue")
        n = int(PlayerX.get())
        score = n + 1
        PlayerX.set(score)
        tkinter.messagebox.showinfo("WINNER X","YOU HAVE JUST WON A GAME!")
        reset()
    if(button1["text"]=="X" and button4["text"]=="X" and button7["text"]=="X"):
        button1.configure(background="sky blue")
        button4.configure(background="sky blue")
        button7.configure(background="sky blue")
        n = int(PlayerX.get())
        score = n + 1
        PlayerX.set(score)
        tkinter.messagebox.showinfo("WINNER X","YOU HAVE JUST WON A GAME!")
        reset()
    if(button2["text"]=="X" and button5["text"]=="X" and button8["text"]=="X"):
        button2.configure(background="sky blue")
        button5.configure(background="sky blue")
        button8.configure(background="sky blue")
        n = int(PlayerX.get())
        score = n + 1
        PlayerX.set(score)
        tkinter.messagebox.showinfo("WINNER X","YOU HAVE JUST WON A GAME!")
        reset()
    if(button3["text"]=="X" and button6["text"]=="X" and button9["text"]=="X"):
        button3.configure(background="sky blue")
        button6.configure(background="sky blue")
        button9.configure(background="sky blue")
        n = int(PlayerX.get())
        score = n + 1
        PlayerX.set(score)
        tkinter.messagebox.showinfo("WINNER X","YOU HAVE JUST WON A GAME!")
        reset()
    if(button1["text"]=="X" and button5["text"]=="X" and button9["text"]=="X"):
        button1.configure(background="sky blue")
        button5.configure(background="sky blue")
        button9.configure(background="sky blue")
        n = int(PlayerX.get())
        score = n + 1
        PlayerX.set(score)
        tkinter.messagebox.showinfo("WINNER X","YOU HAVE JUST WON A GAME!")
        reset()
    if(button3["text"]=="X" and button5["text"]=="X" and button7["text"]=="X"):
        button3.configure(background="sky blue")
        button5.configure(background="sky blue")
        button7.configure(background="sky blue")
        n = int(PlayerX.get())
        score = n + 1
        PlayerX.set(score)
        tkinter.messagebox.showinfo("WINNER X","YOU HAVE JUST WON A GAME!")
        reset()
    elif(button1["text"]=="O" and button2["text"]=="O" and button3["text"]=="O"):
        button1.configure(background="lime")
        button2.configure(background="lime")
        button3.configure(background="lime")
        n = int(PlayerO.get())
        score = n + 1
        PlayerO.set(score)
        tkinter.messagebox.showinfo("WINNER O","YOU HAVE JUST WON A GAME!")
        reset()
    elif(button4["text"]=="O" and button5["text"]=="O" and button6["text"]=="O"):
        button4.configure(background="lime")
        button5.configure(background="lime")
        button6.configure(background="lime")
        n = int(PlayerO.get())
        score = n + 1
        PlayerO.set(score)
        tkinter.messagebox.showinfo("WINNER O","YOU HAVE JUST WON A GAME!")
        reset()
    elif(button7["text"]=="O" and button8["text"]=="O" and button9["text"]=="O"):
        button7.configure(background="lime")
        button8.configure(background="lime")
        button9.configure(background="lime")
        n = int(PlayerO.get())
        score = n + 1
        PlayerO.set(score)
        tkinter.messagebox.showinfo("WINNER O","YOU HAVE JUST WON A GAME!")
        reset()
    elif(button1["text"]=="O" and button4["text"]=="O" and button7["text"]=="O"):
        button1.configure(background="lime")
        button4.configure(background="lime")
        button7.configure(background="lime")
        n = int(PlayerO.get())
        score = n + 1
        PlayerO.set(score)
        tkinter.messagebox.showinfo("WINNER O","YOU HAVE JUST WON A GAME!")
        reset()
    elif(button2["text"]=="O" and button5["text"]=="O" and button8["text"]=="O"):
        button2.configure(background="lime")
        button5.configure(background="lime")
        button8.configure(background="lime")
        n = int(PlayerO.get())
        score = n + 1
        PlayerO.set(score)
        tkinter.messagebox.showinfo("WINNER O","YOU HAVE JUST WON A GAME!")
        reset()
    elif(button3["text"]=="O" and button6["text"]=="O" and button9["text"]=="O"):
        button3.configure(background="lime")
        button6.configure(background="lime")
        button9.configure(background="lime")
        n = int(PlayerO.get())
        score = n + 1
        PlayerO.set(score)
        tkinter.messagebox.showinfo("WINNER O","YOU HAVE JUST WON A GAME!")
        reset()
    elif(button1["text"]=="O" and button5["text"]=="O" and button9["text"]=="O"):
        button1.configure(background="lime")
        button5.configure(background="lime")
        button9.configure(background="lime")
        n = int(PlayerO.get())
        score = n + 1
        PlayerO.set(score)
        tkinter.messagebox.showinfo("WINNER O","YOU HAVE JUST WON A GAME!")
        reset()
    elif(button3["text"]=="O" and button5["text"]=="O" and button7["text"]=="O"):
        button3.configure(background="lime")
        button5.configure(background="lime")
        button7.configure(background="lime")
        n = int(PlayerO.get())
        score = n + 1
        PlayerO.set(score)
        tkinter.messagebox.showinfo("WINNER O","YOU HAVE JUST WON A GAME!")
        reset()
def reset():
    button1["text"]=" "
    button2["text"]=" "
    button3["text"]=" "
    button4["text"]=" "
    button5["text"]=" "
    button6["text"]=" "
    button7["text"]=" "
    button8["text"]=" "
    button9["text"]=" "

    button1.configure(background="gainsboro")
    button2.configure(background="gainsboro")
    button3.configure(background="gainsboro")
    button4.configure(background="gainsboro")
    button5.configure(background="gainsboro")
    button6.configure(background="gainsboro")
    button7.configure(background="gainsboro")
    button8.configure(background="gainsboro")
    button9.configure(background="gainsboro")
def NewGame():
    ng = tkinter.messagebox.askyesno("NEW GAME CONFIRMATION","Are you sure you want to start new game? Your progress won't be saved.")
    if(ng > 0):
        reset()
        PlayerX.set(0)
        PlayerO.set(0)
lblPlayerX = Label(RightFrame1a,font=("courier",40,"bold"),text="PLAYER X:",bd=21,bg="powder blue",fg="black",justify=CENTER)
lblPlayerX.grid(row=0,column=0,sticky=W)
PlayerXp = Label(RightFrame1a,font=("courier",35,"bold"),textvariable=PlayerX,bg="white",fg="black",width=11,padx=5,justify=LEFT)
PlayerXp.grid(row=0,column=1,sticky=W)
lblPlayerO = Label(RightFrame1b,font=("courier",40,"bold"),text="PLAYER O:",bd=21,bg="powder blue",fg="black",justify=CENTER)
lblPlayerO.grid(row=1,column=0,sticky=W)
PlayerOp = Label(RightFrame1b,font=("courier",35,"bold"),textvariable=PlayerO,bg="white",fg="black",width=11,padx=5,justify=CENTER)
PlayerOp.grid(row=1,column=1,sticky=W)

buttonReset = Button(RightFrame2,text="RESET",font=("courier",35,"bold"),fg="black",height=1,width=23,padx=5,pady=13,bg="gainsboro",command=reset)
buttonReset.grid(row=0,column=0,sticky=S+N+E+W)
buttonNew = Button(RightFrame2,text="NEW GAME",font=("courier",35,"bold"),fg="black",height=1,width=23,padx=5,pady=13,bg="gainsboro",command=NewGame)
buttonNew.grid(row=1,column=0,sticky=S+N+E+W)

button1 = Button(LeftFrame,text=" ",font=("courier",30,"bold"),fg="black",height=3,width=8,bg="gainsboro",command=lambda:checker(button1))
button1.grid(row=1,column=0,sticky=S+N+E+W)
button2 = Button(LeftFrame,text=" ",font=("courier",30,"bold"),fg="black",height=3,width=8,bg="gainsboro",command=lambda:checker(button2))
button2.grid(row=1,column=1,sticky=S+N+E+W)
button3 = Button(LeftFrame,text=" ",font=("courier",30,"bold"),fg="black",height=3,width=8,bg="gainsboro",command=lambda:checker(button3))
button3.grid(row=1,column=2,sticky=S+N+E+W)
button4 = Button(LeftFrame,text=" ",font=("courier",30,"bold"),fg="black",height=3,width=8,bg="gainsboro",command=lambda:checker(button4))
button4.grid(row=2,column=0,sticky=S+N+E+W)
button5 = Button(LeftFrame,text=" ",font=("courier",30,"bold"),fg="black",height=3,width=8,bg="gainsboro",command=lambda:checker(button5))
button5.grid(row=2,column=1,sticky=S+N+E+W)
button6 = Button(LeftFrame,text=" ",font=("courier",30,"bold"),fg="black",height=3,width=8,bg="gainsboro",command=lambda:checker(button6))
button6.grid(row=2,column=2,sticky=S+N+E+W)
button7 = Button(LeftFrame,text=" ",font=("courier",30,"bold"),fg="black",height=3,width=8,bg="gainsboro",command=lambda:checker(button7))
button7.grid(row=3,column=0,sticky=S+N+E+W)
button8 = Button(LeftFrame,text=" ",font=("courier",30,"bold"),fg="black",height=3,width=8,bg="gainsboro",command=lambda:checker(button8))
button8.grid(row=3,column=1,sticky=S+N+E+W)
button9 = Button(LeftFrame,text=" ",font=("courier",30,"bold"),fg="black",height=3,width=8,bg="gainsboro",command=lambda:checker(button9))
button9.grid(row=3,column=2,sticky=S+N+E+W)

root.mainloop()
