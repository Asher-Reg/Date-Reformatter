# Date-Reformatter

Receives list of store hours that are formatted as such:

>Mon-Sat: 9:00 am – 11:00 pm\n
>Sun: 10:00 am - 9:00 pm

  Mon-Fri: 10:00 am - 10:00pm
  Sat: 11:00 am - 10:00pm
  Sun: 12:00 pm - 10:00pm
  
And reformats them to look like:

  Monday, Saturday, 10:00 am - 11:00 pm, Sunday, 10:00 am - 9:00 pm
  
  Monday, Friday, 10:00 am - 10:00pm, Saturday, 11:00 am - 10:00 pm, Sunday, 12:00 pm - 10:00 pm
