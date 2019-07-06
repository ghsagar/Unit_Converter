# This application converts kg into grams, puounds, and ounces with GUI
# Tkinter GUI is used here
import tkinter as tk
window=tk.Tk()
window.title("Converter")
def unit_converter():

    to_grams=float(store_entry.get())*1000
    to_pounds = float(store_entry.get()) * 2.20462
    to_ounches = float(store_entry.get())* 35.274
    text_1.delete(1.0,tk.END)
    text_1.insert(tk.END,to_grams)
    text_2.delete(1.0,tk.END)
    text_2.insert(tk.END,  to_pounds)
    text_3.delete(1.0,tk.END)
    text_3.insert(tk.END, to_ounches)
button=tk.Button(command=unit_converter,text="Convert",activebackground="green",activeforeground="white")
button.grid(row=0, column=2)
label_0=tk.Label(text="Enter in Kg")
label_0.grid(row=0,column=0)
store_entry=tk.StringVar()
entry=tk.Entry(window,textvariable=store_entry,width=17,selectbackground="black")
entry.grid(row=0,column=1)
label_1=tk.Label(window,text="In grams")
label_1.grid(row=1,column=0)
text_1=tk.Text(window,height=1, width=13)
text_1.grid(row=1,column=1)

label_2=tk.Label(window,text="In pounds")
label_2.grid(row=2,column=0)
text_2=tk.Text(window,height=1, width=13)
text_2.grid(row=2,column=1)
label_3=tk.Label(window,text="In ounches")
label_3.grid(row=3,column=0)
text_3=tk.Text(window,height=1, width=13)
text_3.grid(row=3,column=1)


window.mainloop()
