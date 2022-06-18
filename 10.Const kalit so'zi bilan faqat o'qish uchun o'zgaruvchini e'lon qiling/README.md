```js
Kalit letso'z o'zgaruvchilarni e'lon qilishning yagona yangi usuli emas. ES6, siz ham constkalit so'z yordamida o'zgaruvchilar e'lon mumkin.

const ega bo'lgan barcha ajoyib xususiyatlarga letega, o'zgaruvchilar yordamida e'lon qo'shimcha bonus constfaqat o'qish bor. Ular doimiy qiymatdir , ya'ni o'zgaruvchi tayinlangandan constso'ng uni qayta tayinlash mumkin emas:

const FAV_PET = "Cats";
FAV_PET = "Dogs";
Konsol tufayli qiymatini qayta tayinlash uchun xato namoyon bo'ladi FAV_PET.

Siz har doim kalit so'z yordamida qayta tayinlashni istamagan o'zgaruvchilarni nomlashingiz constkerak. Bu tasodifan doimiy bo'lishga mo'ljallangan o'zgaruvchini qayta tayinlashga urinishda yordam beradi.

Eslatma: ishlab chiquvchilar o'zgarmas qiymatlar uchun katta o'zgaruvchan identifikatorlardan va o'zgaruvchan qiymatlar (ob'ektlar va massivlar) uchun kichik yoki camelCase-dan foydalanishlari odatiy holdir. Keyingi qiyinchiliklarda ob'ektlar, massivlar va o'zgarmas va o'zgaruvchan qiymatlar haqida ko'proq bilib olasiz. Shuningdek, keyingi qiyinchiliklarda siz katta, kichik yoki camelCase o'zgaruvchan identifikatorlarining misollarini ko'rasiz.

Kodni o'zgartiring, shunda barcha o'zgaruvchilar letyoki yordamida e'lon constqilinadi . letO'zgaruvchining o'zgarishini xohlaganingizda va consto'zgaruvchining doimiy bo'lishini xohlaganingizda foydalaning. Shuningdek, bilan e'lon qilingan o'zgaruvchilarni qayta nomlash constumumiy amaliyotga mos kelish. O'zgaruvchilarga tayinlangan satrlarni o'zgartirmang

```