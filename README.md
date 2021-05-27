def cgpa():
 screen2.destroy()
 global window
 window=Toplevel(screen)
 window.geometry("720x720")
 window.title("CGPA CALCULATION")
 l3=Listbox(window,width=103,height=26,font="AgencyFB 18",bg="light blue")
 l3.grid(row=0,column=0,columnspan=10,rowspan=15)
 l=Label(window,text="Course",bg="skyblue4")
 l.grid(row=0,column=0)
 global c1
 global c2
 global c3
 :
 :
 :
 global c49
 global c50
 global c51
 c1=StringVar()
 e=Entry(window,textvariable=c1)
 e.grid(row=1,column=0)
 l=Label(window,text="CA1",bg="skyblue4")
 l.grid(row=0,column=1)
 c2=IntVar()
 e=Entry(window,textvariable=c2)
 e.grid(row=1,column=1)
 l=Label(window,text="CA2",bg="skyblue4")
 l.grid(row=0,column=2)
 c3=IntVar()
 e=Entry(window,textvariable=c3)
 e.grid(row=1,column=2)
 l=Label(window,text="MTE",bg="skyblue4")
 l.grid(row=0,column=3)
 c4=IntVar()
 e=Entry(window,textvariable=c4) e.grid(row=1,column=3)
 l=Label(window,text="ETE",bg="skyblue4")
 l.grid(row=0,column=4)
 c5=IntVar()
 e=Entry(window,textvariable=c5)
 e.grid(row=1,column=4)
 l=Label(window,text="Att_marks",bg="skyblue4")
 l.grid(row=0,column=5)
 c6=IntVar()
 e=Entry(window,textvariable=c6)
 e.grid(row=1,column=5)
 l=Label(window,text="Credits",bg="skyblue4")
 l.grid(row=0,column=6)
 c7=IntVar()
 e=Entry(window,textvariable=c7)
 e.grid(row=1,column=6)
 c8=StringVar()
 e=Entry(window,textvariable=c8)
 e.grid(row=2,column=0)
 :
 :
 :
 c41=IntVar()
 e=Entry(window,textvariable=c41)
 e.grid(row=6,column=5) 
 c42=IntVar()
 e=Entry(window,textvariable=c42)
 e.grid(row=6,column=6) 
 l=Label(window,text="Marks for PES")
 l.grid(row=7,column=1)
 l=Label(window,text="CA1",bg="skyblue4")
 l.grid(row=8,column=0)
 c43=IntVar()
 e=Entry(window,textvariable=c43)
 e.grid(row=9,column=0)
 l=Label(window,text="CA2",bg="skyblue4")
 l.grid(row=8,column=1)
 c44=IntVar()
 e=Entry(window,textvariable=c44) e.grid(row=9,column=1) 
 l=Label(window,text="CA3",bg="skyblue4")
 l.grid(row=8,column=2)
 c45=IntVar()
 e=Entry(window,textvariable=c45)
 e.grid(row=9,column=2)
 l=Label(window,text="CA4",bg="skyblue4")
 l.grid(row=8,column=3)
 c46=IntVar()
 e=Entry(window,textvariable=c46)
 e.grid(row=9,column=3)
 l=Label(window,text="ETE",bg="skyblue4")
 l.grid(row=8,column=4)
 c47=IntVar()
 e=Entry(window,textvariable=c47)
 e.grid(row=9,column=4)
 l=Label(window,text="Att_marks",bg="skyblue4")
 l.grid(row=8,column=5)
 c48=IntVar()
 e=Entry(window,textvariable=c48)
 e.grid(row=9,column=5)
 l=Label(window,text="Credits",bg="skyblue4")
 l.grid(row=8,column=6)
 c49=IntVar()
 e=Entry(window,textvariable=c49)
 e.grid(row=9,column=6) 
 l=Label(window,text="Marks_for_MGN")
 l.grid(row=10,column=1)
 l=Label(window,text="ETE",bg="skyblue4")
 l.grid(row=11,column=1)
 c50=IntVar()
 e=Entry(window,textvariable=c50)
 e.grid(row=12,column=1)
 l=Label(window,text="Credits",bg="skyblue4")
 l.grid(row=11,column=2)
 c51=IntVar()
 e=Entry(window,textvariable=c51)
 e.grid(row=12,column=2) b3=Button(window, text="Estimate", height=2, width=20, bg="Silver", font=("Garamond",10), 
command=session)
 b3.grid(row=12, column=5)
def session():
 l2=Listbox(window,width=103,height=26,font="AgencyFB 18",bg="light blue")
 l2.grid(row=0,column=0,columnspan=10,rowspan=15) 
 l=Label(window,text="Course",bg="skyblue4")
 l.grid(row=0,column=0)
 l=Label(window,text="TOTAL MARKS",bg="skyblue4")
 l.grid(row=0,column=1)
 l=Label(window,text="GRADE POINTS",bg="skyblue4")
 l.grid(row=0,column=2)
 l=Label(window,text="GRADES",bg="skyblue4")
 l.grid(row=0,column=3)
 l=Label(window,text="CGPA",bg="skyblue4")
 l.grid(row=4,column=4)
 e=Entry(window,textvariable=c1)
 e.grid(row=1,column=0)
 e=Entry(window,textvariable=c8)
 e.grid(row=2,column=0)
 e=Entry(window,textvariable=c15)
 e.grid(row=3,column=0)
 e=Entry(window,textvariable=c22)
 e.grid(row=4,column=0)
 e=Entry(window,textvariable=c29)
 e.grid(row=5,column=0)
 e=Entry(window,textvariable=c36)
 e.grid(row=6,column=0)
 e=Label(window,text="PES")
 e.grid(row=7,column=0)
 e=Label(window,text="MGN")
 e.grid(row=8,column=0)
 m1=c1.get()
 m2=c2.get()
 m3=c3.get()
 :
 :
 : m49=c49.get()
 m50=c50.get()
 m51=c51.get()
 TC=m7+m14+m21+m28+m35+m42+m49+m51
 t1=m7/TC
 t2=m14/TC
 t3=m21/TC
 t4=m28/TC
 t5=m35/TC
 t6=m42/TC
 t7=m49/TC
 t8=m51/TC
 d1=((25*(m2+m3)//60)+(m4//2)+(50*m5//70)+m6)
 d2=((25*(m9+m10)//60)+(m11//2)+(50*m12//70)+m13)
 d3=((25*(m16+m17)//60)+(m18//2)+(50*m19//70)+m20)
 d4=((25*(m23+m24)//60)+(m25//2)+(50*m26//70)+m27)
 d5=((25*(m30+m31)//60)+(m32//2)+(50*m33//70)+m34)
 d6=((25*(m37+m38)//60)+(m39//2)+(50*m40//70)+m41)
 d7=((30*(m43+m44+m45+m45)//120)+(55*m47//100)+m48)
 d8=m50
 if d1>90:
 p1=10
 g1="O"
 elif 80<d1<91:
 p1=9
 g1="A+"
 elif 70<d1<81:
 p1=8
 g1="A"
 elif 60<d1<71:
 p1=7
 g1="B+"
 elif 50<d1<61:
 p1=6
 g1="B"
 elif 45<=d1<51:
 p1=5
 g1="C"
 elif 40<=d1<45: p1=4
 g1="D"
 else:
 p1=3
 g1="E" 
 :
 :
 :
 if d8>90:
 p8=10
 g8="O"
 elif 80<d8<91:
 p8=9
 g8="A+"
 elif 70<d8<81:
 p8=8
 g8="A"
 elif 60<d8<71:
 p8=7
 g8="B+"
 elif 50<d8<61:
 p8=6
 g8="B"
 elif 45<=d8<51:
 p8=5
 g8="C"
 elif 40<=d8<45:
 p8=4
 g8="D"
 else:
 p8=3
 g8="E"
 
 
 
 cgpa=(t1*p1)+(t2*p2)+(t3*p3)+(t4*p4)+(t5*p5)+(t6*p6)+(t7*p7)+(t8*p8)
 
 e=Label(window,text=d1)
 e.grid(row=1,column=1) e=Label(window,text=d2)
 e.grid(row=2,column=1)
 e=Label(window,text=d3)
 e.grid(row=3,column=1)
 e=Label(window,text=d4)
 e.grid(row=4,column=1)
 e=Label(window,text=d5)
 e.grid(row=5,column=1)
 e=Label(window,text=d6)
 e.grid(row=6,column=1)
 e=Label(window,text=d7)
 e.grid(row=7,column=1)
 e=Label(window,text=d8)
 e.grid(row=8,column=1)
 e=Label(window,text=cgpa)
 e.grid(row=5,column=4)
main_screen()
