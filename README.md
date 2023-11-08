# BEM
head <br>
head__eye_green <br>
head__eye_blue <br>
head__mouth_closed <br>


arms <br>
arms__shoulder_left <br>
arms__shoulder_right <br>
arms__wrist_strong <br>

body <br>
body__back_wide <br>
body__chest_pumped <br>
body__abs_strong <br>


legs <br>
legs__knee_left <br>
legs__knee_right<br>
legs__feet_size_9<br>

# Emmet
## Header
![alt text](./img/header.png)<br>
header.header>div.header__wrapper>(div.header__logobox>img.header__logo+p.header__naming)+nav.header__nav>ul.header__list>(li.header__item>a.header__link)*5

## Card
![alt text](./img/cards.png)<br>
main>section.cards>div.cards__wrapper>h2.cards__title+(div.card>img.card__image+h3.card__title+p.card__text)*3

## Reviews
![alt text](./img/reviews.png)<br>
main>section.reviews>div.reviews__wrapper>img.reviews__img+(div.review>p.review__text+img.review__img+p.review__name)*2

## Projects
![alt text](./img/projects.png)<br>
section.projects>div.projects__wrapper>h2.projects__title+(div.project>img.project__img+h3.project__name+p.project__category)*9