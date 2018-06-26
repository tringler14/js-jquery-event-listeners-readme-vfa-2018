//define functions here

function getIt(){
$('p').click(function(){
  alert ("Hey!")
})
}

function frameIt(){
$('img').load(function(){
  $(this).addClass('tasty')
})
}

function pressIt(){
  $("input").on('keydown', function(key){
    if (key.which==71){
      alert("You pressed 'G'!");
  }
    else {return}
  })
}

function submitIt(){
$(document).on('submit', function(){
  alert ("Your form is going to be submitted now.")
})  
  
}

$(document).ready(function (){
getIt();
frameIt();
pressIt();
submitIt();
});
