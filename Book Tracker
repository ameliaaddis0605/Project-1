choice = ""
book_name = ""
pages = int()
hours = ""
book_list = []
hours_list= []
pages_list = []
pages_left_list = []
last_page_list = []

print("Book Reading Tracker")
print("[-------------------]")
print("Track the books you read using this program!")
choice = input("Would you like to add a book? (yes/no) ")

while choice != "no":
  book_name = input("What is the name of the book? ")
  pages = int(input ("How many total pages? "))
  book_list.append(book_name)
  pages_list.append(pages)
  fin = input("Have you finished this book? (finished/unfinished) ")

  if fin == "finished":
    hours = input ("How many hours did it take to finish? ")
    hours_list.append(hours)
    pages_left_list.append(0)
    last_page_list.append(0)

  elif fin == "unfinished":
    last_page = int(input("What page number did you leave off on? "))
    pages_left = pages - last_page
    pages_left_list.append(pages_left)
    hours_list.append("Unfinished")
    last_page_list.append(last_page)

  choice = input("Would you like to add another book? (yes/no) ")

else: 
  print("\nCurrent Book List - ", )  
  for i in range(len(book_list)):
    print("Name:", book_list[i])
    print("Total Pages:", pages_list[i])

    if hours_list[i] == "Unfinished":
      print("Pages Left:", pages_left_list[i])
      print("Last Page Read:", last_page_list[i])
    else:
      print("Total Hours:", hours_list[i])

    print()




