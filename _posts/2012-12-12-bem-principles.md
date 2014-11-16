---
layout: post
title: Про внутренние принципы БЭМ
tags: [BEM, semantic web]
---

Посмотрев на свой код, обнаружил забавную аналогию и скоропалительно сделал несколько выводов.

БЭМ-модификация это не просто пара ключ-значение. Модификация не существуют сама по себе, она всегда привязана к блоку или элементу. Другими словами, присвоение какого-либо свойства или поведения возможно только при наличии объекта. В этом качестве БЭМ-модификация подобна RDF-триплету, коим по сути может являться. Эта аналогия позволяет много интересного нафантазировать про графы, IA и Semantic Web в приложении к интерфейсам и БЭМ, а пока так:

*Следствие 1.* В БЭМ-семантике определяющую роль играет понятие модификации.

*Следствие 2.* Ситуация в которой БЭМ-сущность имеет одну модификацию с несколькими значениями является допустимой. Всё зависит от модификации, т.е. от того какой смысл в неё заложен.

*Следствие 3.* Именно система модификаций-триплетов является одним из принципиальных отличий БЭМ от других систем и фреймворков, допускающих, говоря в БЭМ-терминах, сквозные модификаторы, которые существуют сами по себе (в каком-то отдельном глобальном пространстве) и примешиваются к объектам по мере необходимости.

*Следствие 4.* Явное миксование БЭМ-сущностей лучше неявного.

*Следствие 5.* Связи между АНБ допустимо реализовывать только через явные БЭМ-миксы.