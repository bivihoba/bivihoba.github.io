---
layout: post
title: About semantic differences in markup
tags: [bem, html, css, robots]
redirect_from: "/post/2011/03/653/"
---

Сделал неожиданный для себя вывод: для разработчика, реализующего БЭМ, семантика классов и семантика элементов являются конкурирующими.

С точки зрения написания кода, классы предпочтительнее, на них нет ограничений, ими можно описать все и с необходимой глубиной. Достоинство элементов в общности их семантики. Гипотетически, упразднив элементы, мы скорее всего построим свой набор общих классов с <s>блекджеком</s> аналогичными смыслами. Хотя, подобный набор возникнет в любом случае, поскольку для верстальщика, семантика, привносимая элементами, в большинстве случаев не дает ничего, кроме точки отсчета для своей собственной системы.

А вот для пользовательских агентов интерес представляют только элементы. Возникает вопрос, а надо ли этот интерес удовлетворять? Надо. Да, это [философский вопрос](http://vitaly.ya.ru/replies.xml?item_no=4053).

В итоге получается, что код должен быть написан и для людей и для роботов, и легкого пути не будет, а так хотелось)
