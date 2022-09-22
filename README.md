# WomenSite
Site about popular women made with Django.\
\
This is main page for unauthorized users:\
\
<img width="1400" alt="image" src="https://user-images.githubusercontent.com/67323825/191739362-493b79ed-933d-48db-8d92-69fbd581aaff.png">\
\
For this page I used class - WomenHome.\
\
Authorization page:\
\
<img width="1354" alt="image" src="https://user-images.githubusercontent.com/67323825/191739610-6ab09a14-9b2a-4004-ab43-042aa438eb75.png">\
\
For this page I used class - LoginUser.\
\
Registration page:\
\
<img width="1398" alt="image" src="https://user-images.githubusercontent.com/67323825/191739829-38f9370b-63e8-43de-b028-b8b5c6c8acef.png">\
\
For this page I used class RegisterUser.\
\
When you logged in you can add posts by click 'Добавить статью' on top of page.\
Page for add post:\
\
<img width="1398" alt="image" src="https://user-images.githubusercontent.com/67323825/191740248-dd25362c-329d-4453-8bfe-d4748c0ec36d.png">\
\
For this I used class - AddPage.\
\
Feedback form:\
\
<img width="1400" alt="image" src="https://user-images.githubusercontent.com/67323825/191740480-48078bca-01e4-4aaa-90cc-c9e834fb70d4.png">\
\
For this form I used class - ContactFormView.\
\
My site has pagination:
<img width="1399" alt="image" src="https://user-images.githubusercontent.com/67323825/191741968-50fecb78-bae8-4087-821a-e12382998bdc.png">\
\
All women's photos is stored in folder 'media'. When u add post and add photo to this post, it will be automaticaly saved in this directory.\
\
All templates extends base.html.\
\
All my custom forms you can see in forms.py.\
\
For upper menu I user class DataMixin from utils.py.\
\
Also, I have custom admin panel:\
\
<img width="1399" alt="image" src="https://user-images.githubusercontent.com/67323825/191741638-d169994b-6e02-4760-b54a-fc16062ac5ea.png">\
\
<img width="1401" alt="image" src="https://user-images.githubusercontent.com/67323825/191741705-5c0d27bd-cbe8-43e3-b013-3fe36577fcf1.png">\
\
Finally, I used Django Debug Toolbar to get my code cleaner and faster.
