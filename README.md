# jacking-script

# basic idea

//1    
var ifrm = document.createElement("iframe");    
ifrm.setAttribute("src", "http://target-website.com");    
ifrm.style.width = "640px";    
ifrm.style.height = "480px";    
document.body.appendChild(ifrm);    
//2    
focus on iframe or access iframe contents    
//3 fill details or click    
$('#email').val('email@gmail.com');    
$('#password').val('password');    
$('.login_form').click()    
