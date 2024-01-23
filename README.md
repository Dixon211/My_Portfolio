# My_Portfolio
Here are some of the projects that I'm proud of

1. The Magic Card Identifier was a great way to get my feet wet in OCR. It was also a great learning tool for working with the user to kind of make them optimize the program. While anywhere in the image is able to be checked for text the black borders give the user the impression that the card should be centered which results in the program being able to get better results.

2. The Trading bot was one of my favorites to work on as it was actually my first personal project. Working with a friend I found an unofficial API to the robinhood servers and used that to get and manipulate stock information. We were going for a short selling strategy but unfortunatly the tests were being destroyed by transaction fees unfortunantly. This did however start my journey into machine learning as I was looking into tensor flow and pytorch to change this from short selling into longitudinal perdictions based on webscrapping the news and putting that into a neural network for classification of stocks that would go up and down. In the meantime I have been learning Pytorch and Tensorflow.

3. The database_creation is part of a pair with my ticket autofill project. In my old job the ticketing system was out of date and management had no intention to update it. This meant every ticket needed a trip to our website to get the client info and then you could start working the ticket which really slowed things down. I decided one night to just webscrape the info, format it into a JSON database. There were 2 big challenges to this scraping, logging into the company website and getting the data from non-uniform tables. For the first I used the network tools in edge to find what information the packet was sending to the server and then I crafted a packet for my program to get an authenticated session. I then passed the cookies to all subsequent requests. For the tables I had to filter by words and non-fields which did take a while and needed some manual cleanup after but the time saved was enourmous.

4. the ticket_autofill is the second part of the pair with the database creator. I took the JSON file from the database_creator and then created a chromium web extension. This webextension would listen when the browser was on our ticketing website and if the "edit" button for the tickets was pressed it would check if the ticket was processed by seeing if the info was already there and if it wasn't it would reference the email address from the sender address to the addresses in the JSON database. If it found a match it would fill all the fields automatically. It saved so much time and allowed me to actually get to work on ticket quicker.

5. quick_reply is another chromium web extension I've made that created a new right-click menu item when clicking in an edittable field like a textbox. It would give me the option to fill the field with a preset message that checked the system clock for the time of day for the greeting and then fill with the response selected. It was simple but again it saved tons of time and the headache of writing the same canned response hundreds of times a week.

6. my_website was my second react website. I was really able to make the website much better and am much happier with how clean the layout was. I also was able to do some good photo editting and resizing to work on this which was new for me as a person who most likes working on the backend.
