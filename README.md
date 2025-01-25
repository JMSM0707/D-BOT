# D-BOT
DAWN BOT

- Rasshireniyani ko'chirib olish : [Dawn Validator](https://chromewebstore.google.com/detail/dawn-validator-chrome-ext/fpdkjdnhkakefebpekbdhillbhonfjjp?hl=en)
- Ref kod : p04k1ob5

## Xususiyat

   - Hisob ma'lumotlarini avtomatik olish
  - Agar siz 1 tani tanlasangiz, avtomatik proksi bilan avtomatik ishga tushirish [foydalaning [Monosans Proxy](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/all.txt)]
  - Agar siz 2 ta tanlasangiz, qo‘lda proksi bilan avtomatik ishga tushirish [Ur shaxsiy proksini manual_proxy.txt-ga joylashtirish]
  - Avtomatik da'vo kundalik ro'yxatdan o'tish
  - Har 30 soniyada yurak urishini avtomatik yuborish
  - Har 5 daqiqada avtomatik jo'natish
  - Mavzular bilan ko'p hisoblar

Eslatma: Dawn Server so‘rovlarni qabul qilishda muammolarga duch kelayotgan bo‘lishi mumkin, iltimos, sabr qiling.

## Shart

- Python3.9 dan yuqori va PIP o'rnatilganligiga ishonch hosil qiling.

## O'rnatish

1. **Repozitoriy klonlash:**
   ```bash
   git clone https://github.com/JMSM0707/D-BOT.git
   ```
   ```bash
   cd D-BOT
   ```

2. **O'rnatish talablari:**
   ```bash
   python INSTALL.BAT yoki pip install -r requirements.txt #yoki pip3 install -r requirements.txt
   ```

## Konfiguratsiya

- **accounts.json:** Siz faylni accounts.json loyiha katalogida topasiz. accounts.json unda skript formatiga mos keladigan ma'lumotlar mavjudligiga ishonch hosil qiling, aks holda skript ishlamaydi. Mana fayl formatlariga misollar::
  ```bash
  [
      {
          "Email": "pochta 1",
          "Token": "berear_token 1"
      },
      {
          "Email": "pochta 2",
          "Token": "berear_token 2"
      }
  ]
  ```

- **proxy.txt:** Siz faylni manual_proxy.txt loyiha katalogida topasiz. manual_proxy.txt unda skript formatiga mos keladigan ma'lumotlar mavjudligiga ishonch hosil qiling aks holda skript ishlamaydi. Mana fayl formatlariga misollar:
  ```bash
  http://user:pass@ip:port
  socks4://user:pass@ip:port
  socks5://user:pass@ip:port)
  ```

## Ishga tushurish

```bash
python INSTAL.BAT yoki python bot.py #or python3 bot.py
```

Ushbu omborga tashrif buyurganingiz uchun tashakkur, kuzatishlar va yulduzchalar shaklida hissa qo'shishni unutmang. Savollaringiz bo'lsa, muammolarga duch kelsangiz yoki yaxshilash bo'yicha takliflaringiz bo'lsa, men bilan bog'laning yoki ushbu GitHub omborida muammoni oching.

**JMSM0707**
