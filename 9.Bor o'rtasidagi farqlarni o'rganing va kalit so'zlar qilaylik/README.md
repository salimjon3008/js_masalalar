```js
Kalit so'z bilan o'zgaruvchilar e'lon bilan eng katta muammolardan varbiri osongina o'zgaruvchan deklaratsiyalarini almashtirishni mumkin, deb hisoblanadi:

var camper = "James";
var camper = "David";
console.log(camper);
Yuqoridagi kodda campero'zgaruvchi dastlab e'lon qilinadi Jamesva keyin bekor qilinadi bo'lish David. Konsol keyin mag'lubiyatga ko'rsatadi David.

Kichkina dasturda siz ushbu turdagi muammolarga duch kelmasligingiz mumkin. Lekin sizning codebase katta bo'ladi, deb, agar tasodifan siz niyat qilmagan bir o'zgaruvchining ustiga yozish mumkin. Ushbu xatti-harakatlar xatoga yo'l qo'ymaganligi sababli, xatolarni qidirish va tuzatish qiyinlashadi.

letUshbu potentsial muammoni kalit so'z bilan hal qilish uchun JavaScript-ning asosiy yangilanishi bo'lgan ES6-da kalit so'z kiritildivar. Keyingi muammolarda boshqa ES6 xususiyatlari haqida bilib olasiz.

Agar siz varyuqoridagi kod bilan almashtirsangizlet, bu xatoga olib keladi:

let camper = "James";
let camper = "David";
Xato brauzer konsolida ko'rish mumkin.

Farqli o'laroq var, shuning uchun , qachon foydalanishlet, shu nom bilan bir o'zgaruvchi faqat bir marta e'lon qilinishi mumkin.

Kodni yangilang, shunda u faqat letkalit so'zdan foydalanadi.

```