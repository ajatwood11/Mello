# README

![](screenshot/fello%20copy.png)

A full stack version of the Trello website with jQuery, AJAX, modals, authentication, and drag and drop functionality. When the user first visits the app, they must sign up or login. Once they sign in, they will be brought to their 'My Boards' page. Then they can click on 'New Board', to add a new board via a modal by Micromodal.js. After they add their board, the title will be added to the page. Simply click on the title button to view the board. Then they can click 'Add another list' to add a list. The list will be then posted to the page by an Ajax request. Then they can add a card to that list. So for example, my list is called to-do, then I have all of my daily errands as my cards. By clicking on the title of the list or card they can either delete/edit the list or card. This is also done with Ajax. Each list post, card post, delete method, and edit methods are done through Micromodal.js. At the top of the page you can either click on 'My Boards' or 'Contributors'. 'My Boards' takes you back the boards page. You can add other contributors(colleagues) to your board. This is another modal through Micromodal.js. You simply add the user's email and click 'save'. You can also delete users. If you delete your own account, you will be taken to your 'My Boards' page. Lastly, you can logout through the 'logout' button at the top left.

