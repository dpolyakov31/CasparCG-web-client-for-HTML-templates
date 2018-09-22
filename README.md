# CasparCG-web-client-for-HTML-templates
HTML TEMPLATES WEB CLIENT
We created easy to use and minimalistic Web Client to play/edit/update your html templates on CasparCG server.
Web Client supports preview of HTML templates using browsers <iframe>, so you can control  templates behavior before going on Air.
 you can create playlists to organize titles order, move items inside playlist or append items to playlist.
 We using NodeJS web server to connect Web Client with CasparCG and manipulate file system.
Some rules and restrictions are used for HTML templates to make server and client work stable. 
PS Textfields in your templates marks with id='fn' where 'n' is index of textfield. If you want to have a hint on each textfield in the client use class atribute.Example: "<span class='Name' id='f0'></span>, <span class='Occupation' id='f1'></span>"
