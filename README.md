# Desafio Evaluado - Viajes Chile

se le agrego jquery y una clase especifica para que el navbar parasara de transparente a color

### Jquery
```
$(function (){
    $(window).scroll(function(){
       if ($(this).scrollTop() > 100) {
        $('.navscroll').addClass("azul");
       } else {
        $(".navscroll").removeClass("azul");
       }
    });
});
```

### CSS
```
.navscroll {
    transition:background-color 500ms, color 500ms;
}

.navscroll.azul {
    background-color:#0dc9f0;
    color:white;
}
```
