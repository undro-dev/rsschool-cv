# _My name is Vitali Undro_

> **About myself**

###### My aim is to become a JS developer. I don't have any work experience but I do my best to succeed in studying Java Script programming language. I'm a responsible person who is ready to learn hard and my strong points are: good soft skills, resilience, strong study capability and attention to detail.

> **My skills**

###### JavaScript

###### CSS

###### Git

###### HTML

---

> **My projects**

```$(document).ready(function(){
    $('.carousel__inner').slick({
        speed: 1200,
        adaptiveHeight: true,
        prevArrow: '<button type="button" class="slick-prev"><img src="../img/carusel/chevron-left-solid.jpg"</button>',
        nextArrow: '<button type="button" class="slick-next"><img src="../img/carusel/chevron-right-solid.jpg"</button>',
        responsive: [
            {
                breakpoint: 992,
                settings: {
                    dots: true,
                    arrows: false
            }
        }
        ]

    });

    $('ul.catalog__tabs').on('click', 'li:not(.catalog__tab_active)', function() {
        $(this)
          .addClass('catalog__tab_active').siblings().removeClass('catalog__tab_active')
          .closest('div.container').find('div.catalog__content').removeClass('catalog__content_active').eq($(this).index()).addClass('catalog__content_active');
      });


      $('.catalog-item__link').each(function(i) {
          $(this).on('click', function(e) {
              e.preventDefault();
              $('.catalog-item__content').eq(i).toggleClass('catalog-item__content_active');
              $('.catalog-item__list').eq(i).toggleClass('catalog-item__list_active');
          })
      });
```

---

> **Education**

###### Online courses BEONMAX:

###### HTML / CSS

###### JavaScript

###### Git

> **My contacts**

###### E-mail: vitalyundro@gmail.com

###### Telegram: https://t.me/Vitali_Undro

---
> **My English level - A2**
