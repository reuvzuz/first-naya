# first-naya
root =Tk()
root.title (kalkulator)
#הגדרת מחשבון 
def calk(key)
  global memory
  if key =="=":
     strl ="-+*/0123456789c"
     if calc_entry.get()[0] not in strl:
        calc_entry.insert(END " נא להכניס מספר")
        messagebox.showerror("טעות הקלדת מספר")
#פסילת טעויות הקלדה
     try:
     result = eval(call_entry.get())
     cal_entry.insert(END, "=" +str(result))
     except:
     calc_entry.insert(END,"טעות")
     messagebox.showerror("טעות הזנה")
#reset
  elif key == "C":
  calc_entry.delete(0,END)
#החלפת +ל- 
   elif key == "+/-"
      if "=" in calc_entry.get():
         calc_entry.delete(0,END)
      try:
          if calc_entry.get()[0] == "-":
            calc_entry.delete(0,"-")
          else:
              calc_entry.insert(0,"-")
      exept IndexError:
          pass
    else
        if"=" in calc_entry.get():
            calc_entry.insert (END, key)
    
print ('שלום')
print ('מה אתה רוצה ללמוד ?')
print ('ללוח כפל השק 1')
print ('לשאלות ותתשובות הקש 2')
print ('ללמוד שיר הקש 3')
#יש יכולת קליטת עברית ואיך אפשר להגדיר עברית ?
num=i
 if i!=1,2,3
  print ('בחירה לא נכונה')
 if i==1
   print('בוא נתחיל')
     # מעבר ללוח  כפל
   #הגדרת כפטורים ופרמטרים של כפל חילוק וכו 
     bttn_list = [
        "7","8","9","+","-",
        "4","5","6","*","/",
        "0",".","c","",""
                  ]
        r=1
        c=0
        for i in bttn_list:
        rel = ""
         cmd=lamda x=i: #(calk)הגדרת כפתורי מחשבון 
        ttk.Butom(root, text=i,comand=cmd).grid(row=r, columb=c)
        c +=1
        if c>4
           c=0
           r +=1
        calc_entry = Entry(root,width=33)
        calc_entry.grid(row=0, colum=0, columspan=5)

   root.mainloop() 
   
   #בחירת שלב 2 של תפריט הראשי
       if i===2
  print('בוא נתחיל')
    #מעברת לשאלות ותשובות 
  if i==3 
  print('בוא נתחיל')
#בחירת של 3 של התפריט הראשית 
  
    #מעברר ללמוד שיר 
  else break
#תחילת מערך לוח כפל


#צירוף קובץ עם שאלות ותשובות 
  import qwe.txt
#לעלות מילים של שיר 
  iport song.txt 
  
     
