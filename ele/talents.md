---
title: Таланты Шамана Стихии
layout: page
last_update: 2021-03-18
wow: 9.0.5
toc: true
author: Amani
---

# Таланты для рейда

Билд талантов, предназначенный для боя против одной цели. Некоторые таланты могут варьироваться в зависимости от босса, уточняйте информацию по каждому бою на [WarcraftLogs](https://www.warcraftlogs.com/).

{% include talents.html data=site.data.talents.ele active="2311332" %}

* **45 уровень:** Если вам сложно не терять стаки таланта {{ site.data.spells.if }} и уследить за всеми КД, используйте талант {{ site.data.spells.primal_elem }}, потери ДПС будут не критичны.

# Таланты для Мифик+

{% include talents.html data=site.data.talents.ele active="2111322" %}

* **25 уровень:** {{ site.data.spells.afs }} является стандартным выбором, так как крайне полезен на АоЕ, особенно в сочетании с легендаркой {{ site.data.legend.eogs }}. {{ site.data.spells.eb }} можно брать в подземелья, где большинство боев идут против **1-3** целей, например Театр Боли.

* **30 уровень:** Ситуативный тир, выбирайте между {{ site.data.spells.spirit_wolf }} и {{ site.data.spells.static }}.

# Разбор талантов

## Первый тир, 15 уровень

{% include talents.html data=site.data.talents.ele active="110" row=1 %}

<a href="https://ru.wowhead.com/spell=170374" target="blank" data-wh-icon-size="medium" >**Возмущение земли**</a> – пассивный талант, который наносит небольшой урон одной цели.

* **Подойдет исключительно под АоЕ бой в сочетании с талантом {{ site.data.spells.storm }} .**

* Нанесение урона от этого таланта длится **6** секунд и срабатывает от любого атакующего заклинания.
* Урон наносится примерно раз в **1** секунду, увеличиваясь от Скорости, со случайными промежутками времени между атаками.
* Копия Искусности из **Warlords of Draenor**.

<a href="https://ru.wowhead.com/spell=333919" target="blank" data-wh-icon-size="medium" >**Эхо стихий**</a> – пассивный талант, дает второй заряд для способности {{ site.data.spells.lvb }}.

* **Лучший и самый универсальный талант в этом тире.**

* Сокращает кулдаун {{ site.data.spells.lvb }} до **8** секунд, вместо «**8** секунд + время произнесения + время реакции».
* Позволяет не терять время перезарядки при проке {{ site.data.spells.lava_surge }}.
* Бесполезен на большом АоЕ (**5+** целей), так как там мы практически не используем  {{ site.data.spells.lvb }}.

<a href="https://ru.wowhead.com/spell=342243" target="blank" data-wh-icon-size="medium" >**Статический разряд**</a> – активная способность, наносит урон одной цели с КД **30** секунд.

* Считайте, что этого таланта не существует.

## Второй тир, 25 уровень

{% include talents.html data=site.data.talents.ele active="111" row=2 %}

<a href="https://ru.wowhead.com/spell=273221" target="blank" data-wh-icon-size="medium" >**Повторный толчок**</a> – пассивный талант, дает **25%** шанс вернуть всю затраченную Энергию Водоворота при использовании способностей {{ site.data.spells.es }} и {{ site.data.spells.quake }}.

* **Лучший таланта для Мифик+.**

* Лучше всего раскрывает себя на АоЕ, где мы можем генерировать гораздо больше энергии Водоворота за счет способности {{ site.data.spells.cl }}.
* В бою против одной цели проигрывает {{ site.data.spells.eb }}, так как {{ site.data.spells.es }} не является нашим основным источником урона.

<a href="https://ru.wowhead.com/spell=320125" target="blank" data-wh-icon-size="medium" >**Вторящий шок**</a> – активный талант с КД **30** секунд, который дублирует следующее использованное вами заклинание.

* **Лучший талант для PvP, но бесполезен в Рейде и Мифик+.**

* На одну цель следует дублировать {{ site.data.spells.es }}, а на две и более целей – {{ site.data.spells.quake }}.
* Ни в коем случае не дублируйте {{ site.data.spells.lb }} под баффом от {{ site.data.spells.sk }}, иначе вы потеряете один стак этого таланта. А если применить на второй заряд, то дублируется обычная {{ site.data.spells.lb }}, а не усиленная.
* Если дублировать {{ site.data.spells.fs }}, то он просто повесится на эту же цель, что тоже не рекомендуется.
* Если дублировать способность ковенанта <span style="color:#40bf40;font-size:1em;">Некролордов</span> {{ site.data.covenants.pw }}, то этот талант повторит только часть с {{ site.data.spells.fs }}, дополнительного баффа не будет.
* Срабатывает на {{ site.data.spells.hs }}, причем без затрат маны.
* Дублирует только базовое заклинание, без каких-либо баффов. 

<a href="https://ru.wowhead.com/spell=117014" target="blank" data-wh-icon-size="medium" >**Удар духов стихий**</a> – активная способность с коротким кулдауном, наносит средний урон и дает бафф к случайной характеристике, а также генерирует Энергию Водоворота.

* **Лучший талант для боя против одной цели.**

* Используется в рейде практически на всех боссах, а также находит применение в некоторых подземельях, например в Театре Боли.
* При проке Искусности {{ site.data.spells.elem_mastery }} бафф всегда дается на две различные характеристики. 
* В бою против **1-3** целей {{ site.data.spells.eb }} следует использовать по КД, но только если это не приведет к оверкапу энергии Водоворота.
* На **4+** целях этот талант практически бесполезен, так как {{ site.data.spells.cl }} будет полезнее.
* Поглощает бафф от таланта {{ site.data.spells.mote }}, соответственно усиливая свой урон.
* Генерирует достаточно много энергии Водоворота, что отлично сочетается с нашими легендарками {{ site.data.legend.lava }} и {{ site.data.legend.eogs }}, но на АоЕ проигрывает {{ site.data.spells.afs }}.

## Третий тир, 30 уровень

{% include talents.html data=site.data.talents.ele active="111" row=3 %}

<a href="https://ru.wowhead.com/spell=260878" target="blank" data-wh-icon-size="medium" >**Дух волка**</a> – пассивный талант, снижает получаемый урон и увеличивает скорость передвижения в форме [Призрачного волка](https://ru.wowhead.com/spell=2645).

* **Полезен в любом типе контента.** 

* Накапливает по **5%** эффективности раз в секунду, до максимума в **20%**.

<a href="https://ru.wowhead.com/spell=974" target="blank" data-wh-icon-size="medium" >**Щит земли**</a> – активный талант, накладывает щит, который лечит цель при получении урона. Имеет **9** зарядов, после чего его следует обновлять.

* **Используется в основном в PvP, в PvE практически бесполезен.**

* Требует тратить ГКД для активации, что приводит к снижению наносимого урона.
* Не сочетается с [Щитом молний](https://ru.wowhead.com/spell=192106), так как активен может быть только один щит одновременно.

<a href="https://ru.wowhead.com/spell=265046" target="blank" data-wh-icon-size="medium" >**Статический разряд**</a> – пассивный талант, сокращает время восстановления [Тотема конденсации](https://ru.wowhead.com/spell=192058) на **5** секунд за каждого пораженного врага, не более **4**.

* **Отличный выбор в Мифик+**

* При попадании [Тотемом конденсации](https://ru.wowhead.com/spell=192058) по **4+** врагам, КД сократится до **40** секунд.

## Четвертый тир, 35 уровень

{% include talents.html data=site.data.talents.ele active="110" row=4 %}

<a href="https://ru.wowhead.com/spell=16166" target="blank" data-wh-icon-size="medium" >**Властелин стихий**</a> – пассивный талант, увеличивает урон от различных заклинаний на **20%** после применения [Выброса лавы](https://ru.wowhead.com/spell=51505).

* **Лучший талант этого тира для всех типов контента.**

* Работает на следующие способности:
  * **Сила природы** – {{ site.data.spells.es }}, {{ site.data.spells.lb }}, {{ site.data.spells.cl }}.
  * **Магия льда** – {{ site.data.spells.frs }}, {{ site.data.spells.if }}.
  * **Физический урон** – {{ site.data.spells.quake }}.
* Не работает на магию огня, то есть не усиливает {{ site.data.spells.lvb }} и {{ site.data.spells.fs }}.
* Бафф появляется сразу же после завершения каста [Выброса лавы](https://ru.wowhead.com/spell=51505), а не в момент попадания снаряда в цель.
* **Важный момент!** Если у вас есть два заряда [Выброса лавы](https://ru.wowhead.com/spell=51505), то не следует кастовать между ними обычную [Молнию](https://ru.wowhead.com/spell=188196), так как это приведет к потере урона. Это связано с тем, что если в момент применения [Молнии](https://ru.wowhead.com/spell=188196) у вас прокнет {{ site.data.spells.lava_surge }}, то вы потеряете часть КД на {{ site.data.spells.lvb }}.
* Но это правило не распространяется на мгновенные заклинания – усиленная {{ site.data.spells.lb }} от таланта {{ site.data.spells.sk }}, усиленный {{ site.data.spells.frs }} от таланта {{ site.data.spells.if }}, а также {{ site.data.spells.es }} и {{ site.data.spells.quake }}. Поглощайте бафф от [Властелина стихий](https://ru.wowhead.com/spell=16166) этими заклинаниями, даже если у вас уже есть один стак [Выброса лавы](https://ru.wowhead.com/spell=51505).
* Проще говоря – не стоит кастовать обычную [Молнию](https://ru.wowhead.com/spell=188196), если у вас есть заряд [Выброса лавы](https://ru.wowhead.com/spell=51505). Бафф от таланта {{ site.data.spells.mote }} не перекроет потенциальную потерю урона при проке {{ site.data.spells.lava_surge }}

* Приоритет способностей для баффа [Властелином стихий](https://ru.wowhead.com/spell=16166):
1. {{ site.data.covenants.ft }}
2. {{ site.data.spells.quake }} на **2** и более целях.
3. {{ site.data.spells.lb }} под баффом {{ site.data.spells.sk }}
4. {{ site.data.spells.es }}
5. {{ site.data.spells.frs }} под баффом {{ site.data.spells.if }}
6. {{ site.data.spells.eb }} **Важно!** {{ site.data.spells.eb }} используется всегда по кулдауну, вне зависимости от наличия или отсутствия баффа {{ site.data.spells.mote }}.  
7. {{ site.data.spells.lb }}
8. {{ site.data.spells.if }}
9. {{ site.data.spells.frs }}

<a href="https://ru.wowhead.com/spell=192249" target="blank" data-wh-icon-size="medium" >**Элементаль бури**</a> – пассивный талант, заменяет [Элементаля огня](https://ru.wowhead.com/spell=198067). Сокращает время прознесения [Молнии](https://ru.wowhead.com/spell=188196) и [Цепной молнии](https://ru.wowhead.com/spell=188443) на **3%**, вплоть до **60%**.

* **Сильный талант для Мифик+, но только в организованной группе**. 

* Используется только в сочетании с талантом шестого тира – {{ site.data.spells.primal_elem }}, что превращает его в отличную способность, особенно на АоЕ.
* Так как {{ site.data.spells.storm }} заменяет [Элементаля огня](https://ru.wowhead.com/spell=198067), вы лишаетесь продления длительности и ускоренных тиков [Огненного шока](https://ru.wowhead.com/spell=188389).
* Несмотря на уменьшение скорости произнесения [Молнии](https://ru.wowhead.com/spell=188196) при активном [Элементале бури](https://ru.wowhead.com/spell=192249), в бою против одной цели мы все равно кастуем {{ site.data.spells.lvb }}, вплоть до **18** стаков [Порыва ветра](https://ru.wowhead.com/spell=263806).
* На АоЕ, во время активного [Элементаля бури](https://ru.wowhead.com/spell=192249), спамим [Цепную молнию](https://ru.wowhead.com/spell=188443) и тратим энергию Водоворота на {{ site.data.spells.quake }}.

<a href="https://ru.wowhead.com/spell=192222" target="blank" data-wh-icon-size="medium" >**Тотем жидкой магмы**</a> – активный талант, тотем со временем восстановления **1** минута, который наносит АоЕ урон в определенном месте в течение **15** секунд.

* **Достаточно слабый талант на данный момент.**

* {{ site.data.spells.lmt }} невозможно передвинуть после установки (в отличие, например, от {{ site.data.covenants.vt }} Кирий).
* Наносит неплохой урон раз в минуту, но только в том случае, если мобы проживут все время действия тотема и не выбегут из него.

## Пятый тир, 40 уровень

{% include talents.html data=site.data.talents.ele active="111" row=5 %}

<a href="https://ru.wowhead.com/spell=30884" target="blank" data-wh-icon-size="medium" >**Страж природы**</a> – пассивный талант, исцеляет вас на **20%**, когда уровень вашего здоровья падает ниже **35%** от максимального запаса.

* **Берется по умолчанию, если не требуется дополнительное утилити от других талантов этого тира.**
* Этот талант может спасти от смерти в том случае, если количество избыточного урона не превысило количество его исцеления.
* Талант достаточно силен, но его срабатывание не всегда получается контролировать, так как он имеет внутренний кулдаун в **45** секунд.

<a href="https://ru.wowhead.com/spell=108281" target="blank" data-wh-icon-size="medium" >**Наставления предков**</a> – активная способность, лечит **трех** союзников на **25%** от нанесенного урона в течение **10** секунд раз в **2** минуты.

* **Будет полезен в Мифик+** для отхила аффикса {{ site.data.spells.prideful }}, а также в сочетании с [Цепной жатвой](https://ru.wowhead.com/spell=320674) <span style="color:#ff4040;font-size:1em;">Вентиров</span>.
* Не имеет ГКД, следовательно использование этой способности не снижает наносимый урон за счет потерянного каста.
* Работает в том числе и на отхил, например от {{ site.data.spells.hs }} или {{ site.data.spells.ch }}.

 <a href="https://ru.wowhead.com/spell=192077" target="blank" data-wh-icon-size="medium" >**Тотем ветряного порыва**</a> – активный талант, устанавливает тотем в указанном месте, увеличивающий скорость передвижения любого союзника, зашедшего в зону его действия, на **60%** в течение **5** секунд.

* **Лучший выбор для рейда, если вы знаете где ставить этот тотем.**
* Это очень сильная способность, крайне полезная в боях, где от группы требуется быстро переместиться из точки А в точку Б.
* Ценность этого таланта растет при отсутствии в вашей группе друида, способного ускорить группу при помощи {{ site.data.spells.stampeding_roar }}.
* Игрок, повторно зашедший в область действия тотема, обновит время действия баффа.
* Тотем можно разместить по ходу движения группы.

## Шестой тир, 45 уровень

{% include talents.html data=site.data.talents.ele active="011" row=6 %}

<a href="https://ru.wowhead.com/spell=262303" target="blank" data-wh-icon-size="medium" >**Прилив мощи**</a> – пассивный талант, усиливает одно из четырех наших заклинаний после применения [Земного шока](https://ru.wowhead.com/spell=8042).

* {{ site.data.spells.fs }} – накладывает второй дебафф на соседнюю цель в радиусе **8** метров от основной.
  * В первую очередь выбирает цели без [Огненного шока](https://ru.wowhead.com/spell=188389).
  * Если на всех целях в радиусе уже есть дебафф, то вешается на цель с наименьшей оставшейся длительностью.

<p></p>

* {{ site.data.spells.lb }} – добавляет дополнительные эффекты перегрузки, как при срабатывании Искусности {{ site.data.spells.elem_mastery }}.
  * Количество проков определяется шансом: **80%** на **1** перегрузку, **18%** на **2** перегрузки и **2%** на **3** перегрузки.
  * Не зависит от стандартного шанса перегрузки от Искусности, вероятность на его прок расчитывается отдельно. 
  * Максимум за одну [Молнию](https://ru.wowhead.com/spell=188196) может вылететь **4** прока Искусности, если очень сильно повезет.
  * Сочетается с талантом {{ site.data.spells.sk }}, добавляя дополнительную перегрузку усиленной [Молнии](https://ru.wowhead.com/spell=188196), но требует наличия **90+** энергии Водоворота для реализации обоих стаков.

<p></p>

* {{ site.data.spells.lvb }} – снижает оставшийся КД [Элементаля огня](https://ru.wowhead.com/spell=198067) / [Элементаля бури](https://ru.wowhead.com/spell=192249) на **6** секунд.
  * Самый слабый вариант использования этого таланта, и подходит только в том случае, если вы точно знаете время боя и сколько необходимо кастануть усиленных [Выбросов лавы](https://ru.wowhead.com/spell=51505).

<p></p>

* {{ site.data.spells.frs }} – замораживает цель на одном месте на **6** секунд.
 * Эффект заморозки не прерывается при нанесении урона.

* **Крайне нишевый талант, на данный момент используется только в Торгасте**, так как позволяет вызывать одновременно [Элементаля земли](https://ru.wowhead.com/spell=198103) и [Элементаля огня](https://ru.wowhead.com/spell=198067).
* И в PvE, и PvP контенте проигрывает другим талантам этого тира.

<a href="https://ru.wowhead.com/spell=117013" target="blank" data-wh-icon-size="medium" >**Повелитель изначальных стихий**</a> – усиливает наших элементалей, увеличивая наносимый ими урон на **80%** и превращает их в питомцев с различными активными способностями.

* Усиленный {{ site.data.spells.fe }} получает следующие способности:
  * [Огненный взрыв](https://ru.wowhead.com/spell=57984/) – основная атака по одной цели, наносит **121.5%** урона от силы заклинаний. Базовое время произнесения **3** секунды. Кастуется элементалем автоматически.
  * [Жертвенный огонь](https://ru.wowhead.com/spell=118297) – ДоТ эффект на одну цель, с КД **10** секунд и временем произнесения **2** секунды. Наносит **36%** урона от силы заклинаний при наложении и **94.5%** урот от силы заклинаний в течение **21** секунд. Кастуется элементалем автоматически по КД.
  * {{ site.data.spells.meteor }} – активная способность, прожимается игроком с панели питомца или с помощью [макроса](https://stormkeeper.ru/info/macros.html#%D1%81%D1%82%D0%B8%D1%85%D0%B8%D0%B8). Наносит **135%** урона от силы заклинаний **8** противникам в радиусе **10** метров от основной цели. Если использовать это заклинание, пока {{ site.data.spells.fe }} произносит [Огненный взрыв](https://ru.wowhead.com/spell=57984/) или [Жертвенный огонь](https://ru.wowhead.com/spell=118297), то их каст прервется и начнется заново. Придерживайте использование этой способности под дополнительных аддов, если они появятся в течение жизни [Элементаля огня](https://ru.wowhead.com/spell=198067), либо используйте сразу с пула в бою против одной цели (пока активны различные баффы типа {{ site.data.covenants.lead }} или {{ site.data.loot.Potion_of_Spectral_Intellect }}).

<p></p>

* {{ site.data.spells.storm }} получает следующие способности:
  * [Порыв ветра](https://ru.wowhead.com/spell=157331) – основная атака по одной цели, наносит **27%** урона от силы заклинаний. Базовое время произнесения **3** секунды. Применяется элементалем автоматически.
  * [Призыв молнии](https://ru.wowhead.com/spell=157348) – бафф всего урона [Элементаля бури](https://ru.wowhead.com/spell=192249) на **300%**, кастуется автоматически, сразу после призыва. Также наносит **54%** урона от силы заклинаний. Время восстановления **10** секунд.
  * [Око шторма](https://ru.wowhead.com/spell=157375/) – активная способность, прожимается игроком с панели питомца или с помощью [макроса](https://stormkeeper.ru/info/macros.html#%D1%81%D1%82%D0%B8%D1%85%D0%B8%D0%B8). Раз в секунду наносит **18%** урона от силы заклинаний цели и противникам вокруг неё, максимум **6** целей. Урон усиливается на **5%** каждый раз, когда эта способность наносит урон. Перед использованием убедитесь, что [Элементаля бури](https://ru.wowhead.com/spell=192249) использовал на себя [Призыв молнии](https://ru.wowhead.com/spell=157348) и имеет бафф на **300%** наносимого урона!


<p></p>

* {{ site.data.spells.igor }} получает следующие способности:
  * [Разгневанный дух земли](https://ru.wowhead.com/spell=36213) – АоЕ таунт всех противников (кроме боссов) раз в **5** секунд в радиусе **15** метров. Применяется элементалем автоматически.
  * [Раздавить](https://ru.wowhead.com/spell=118345/) – оглушение одной цели на **4** секунды. Применяется автоматически сразу после вызова [Элементаля земли](https://ru.wowhead.com/spell=198103). Имеет время восстановления **40** секунд, то есть применяется два раза за один призыв элема.
  * [Каменные доспехи](https://ru.wowhead.com/spell=118337/) – активная способность, прожимается игроком с панели питомца или с помощью [макроса](https://stormkeeper.ru/info/macros.html#%D1%81%D1%82%D0%B8%D1%85%D0%B8%D0%B8). Уменьшает получаемый урон [Элементалем земли](https://ru.wowhead.com/spell=198103) и **игроком** на **40%** на **10** секунд. Элементаль применяет эту способность автоматически, когда у него остается мало здоровья. В сочетании с [Астральным сдвигом](https://ru.wowhead.com/spell=108271/) снижает получаемый игроком урон на **64%**.

<p></p>

* Лучший талант для АоЕ боев, но не плох также и в бою против одной цели, к тому же он проще, чем {{ site.data.spells.if }}.
* Нельзя призвать двух усиленных элементалей, так как они считаются питомцами, а не стражами. При призыве нового старый элементаль пропадает.
* Если отключить автокаст у одного элементаля, например АоЕ таунт [Разгневанный дух земли](https://ru.wowhead.com/spell=36213), то у другого не будет работать автокаст его абилки в том слоте, например [Огненный взрыв](https://ru.wowhead.com/spell=57984/).
* Усиленный {{ site.data.spells.fe }} отлично сочетается с легендаркой {{ site.data.legend.fire }} и наносит неплохой урон.
* Усиленный {{ site.data.spells.storm }} является очень сильным АоЕ кулдауном как за счет ускорения кастов [Цепной молнии](https://ru.wowhead.com/spell=188443), так и за счет способности [Око шторма](https://ru.wowhead.com/spell=157375/).
* Усиленный {{ site.data.spells.igor }} дает нам дополнительный сейв, который пригодится в любом типе контента. Также он может помочь в Мифик+, например если танк мертв или ему надо снять с себя стаки на [Некротическом](https://ru.wowhead.com/affix=4) аффиксе.

<a href="https://ru.wowhead.com/spell=210714" target="blank" data-wh-icon-size="medium" >**Ледяная ярость**</a> – активная способность, наносит небольшой урон, дает **25** ед. энергии Водоворота и усиливает **4** следующих [Ледяных шока](https://ru.wowhead.com/spell=196840) на **300%**, которые также генерируют **8** ед. энергии Водоворота. Бафф висит **15** секунд, время восстановления способности **30** секунд.

* **Лучший талант для боя против одной цели.**
* Поначалу использование этого таланта может вызывать трудности, так как делает ротацию более сложной.
* {{ site.data.spells.if }} следует кастовать практически по кулдауну, а не только перед перебежками.
* После использования [Ледяной ярости](https://ru.wowhead.com/spell=210714) представьте, что вместо четырех следующих [Молний](https://ru.wowhead.com/spell=188196) вам нужно использовать четыре [Ледяных шока](https://ru.wowhead.com/spell=196840).
* В идеале, каждый усиленный {{ site.data.spells.frs }} следует бафать талантом {{ site.data.spells.mote }}. 
* Не придерживайте стаки слишком долго, так как **потерять стак баффа [Ледяной ярости](https://ru.wowhead.com/spell=210714) гораздо хуже, чем потерять бафф от [Властелина стихий](https://ru.wowhead.com/spell=16166).**

## Седьмой тир, 50 уровень

{% include talents.html data=site.data.talents.ele active="010" row=7 %}

<a href="https://ru.wowhead.com/spell=260895" target="blank" data-wh-icon-size="medium" >**Безграничная мощь**</a> – пассивный талант, при каждом проке перегрузки от Искусности {{ site.data.spells.elem_mastery }}, вы получете бафф на **2%** Скорости. При получении эффекта время действия не обновляется.

* **На данный момент этот талант не используется ни в каком типе контента.**

<a href="https://ru.wowhead.com/spell=191634" target="blank" data-wh-icon-size="medium" >**Хранитель бурь**</a> – активный талант, бурст с кулдауном **1** минута. Дает **2** заряда баффа, который усиливает следующую [Молнию](https://ru.wowhead.com/spell=188196) на **150%**, а также позволяет применить [Молнию](https://ru.wowhead.com/spell=188196) и [Цепную молнию](https://ru.wowhead.com/spell=188443) мгновенно, вызвав при этом срабатывание Искусности {{ site.data.spells.elem_mastery }} на каждой цели. Бафф висит **15** секунд.

* **Самый сильный талант этого тира, лучший выбор во все типы контента.**

* Дает отличный бурст как по одной цели, так и на АоЕ.
* Не зависит от передвижения, как другие таланты этого тира.
* Каждую усиленную [Молнию](https://ru.wowhead.com/spell=188196) и [Цепную молнию](https://ru.wowhead.com/spell=188443) желательно бафать [Властелином стихий](https://ru.wowhead.com/spell=16166).
* На **1-2** цели следует использовать [Молнию](https://ru.wowhead.com/spell=188196), а на **3+** уже [Цепную молнию](https://ru.wowhead.com/spell=188443), как и во время обычной [ротации](https://stormkeeper.ru/ele/rotation.html).
* Вы можете придерживать кулдаун [Хранителя бурь](https://ru.wowhead.com/spell=191634) под важные моменты боя, например сломанная колонная на [Грязешмяке](https://stormkeeper.ru/ele/nathria.html#%D0%B3%D1%80%D1%8F%D0%B7%D0%B5%D1%88%D0%BC%D1%8F%D0%BA) или на копии Баргаста в бою против [Ловчего Альтимора](https://stormkeeper.ru/ele/nathria.html#%D0%BB%D0%BE%D0%B2%D1%87%D0%B8%D0%B9-%D0%B0%D0%BB%D1%8C%D1%82%D0%B8%D0%BC%D0%BE%D1%80-%D1%8D%D0%BF%D0%BE%D1%85%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D0%B9-%D1%80%D0%B5%D0%B6%D0%B8%D0%BC).
* Количество получаемой энергии Водоворота и наносимый урон в зависимости от количества пораженных целей:
1. {{ site.data.spells.lb }} по **1** цели дает **11** энергии Водоворота и наносит **439.3%** урона от силы заклинаний.
2. {{ site.data.spells.cl }} по **2** целям дает **20** энергии Водоворота и наносит **253.8%** урона от силы заклинаний.
3. {{ site.data.spells.cl }} по **3** целям дает **39** энергии Водоворота и наносит **500.55%** урона от силы заклинаний.
4. {{ site.data.spells.cl }} по **4** целям дает **64** энергии Водоворота и наносит **827.2%** урона от силы заклинаний.
5. {{ site.data.spells.cl }} по **5** целям дает **95** энергии Водоворота и наносит **1233.75%** урона от силы заклинаний. 

<p></p>

* Для сравнения: {{ site.data.spells.cl }} без баффа от [Хранителя бурь](https://ru.wowhead.com/spell=191634) и без учета Искусности наносит **235%** урона от силы заклинаний по **5** целям, а {{ site.data.spells.quake }} в одну цель наносит **138%** урона от силы заклинаний, то есть **690%** урона от силы заклинаний по **5** целям. 

<a href="https://ru.wowhead.com/spell=114050" target="blank" data-wh-icon-size="medium" >**Перерождение**</a> – активная бурст-способность, со временем восстановления **3** минуты. В течение **15** секунд позволяет использовать {{ site.data.spells.lvb }} без кулдауна и он наносит дополнительный урон, равный вашей вероятности критического удара. При активации обновляет {{ site.data.spells.fs }} на всех целях и использует на них {{ site.data.spells.lvb }}.

* **Слабый талант, на данный момент его можно использовать только в Торгасте.**

* Проигрывает [Хранителю бурь](https://ru.wowhead.com/spell=191634) практически по всем параметрам – урон, кулдаун, удобство использования, влияние передвижения и т.д.
* Этот талант практически бесполезен на АоЕ, так как [Поток лавы](https://ru.wowhead.com/spell=114074), в который под действием [Перерождения](https://ru.wowhead.com/spell=114049) превращается {{ site.data.spells.cl }}, крайне слабый бафф, учитывая, что основной урон мы наносим за счет [Землетрясения](https://ru.wowhead.com/spell=61882).
* В случае перебежки, чтобы не терять урон от этого таланта, необходимо использовать {{ site.data.spells.swg }}, а также придерживать его кулдаун в течение минуты под следующее {{ site.data.spells.asc_ele}}. В итоге мы теряем пользу от очень приятного баффа для кастов на ходу, так как он слишком долго простаивает без кулдауна.
