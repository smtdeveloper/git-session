# git-session

GIT KOMUTLARI
---------------

 - KULLANICI BILGILERI :
    
    git config --global user.name "kullanıcı adı / rumuz" <br>
    git config --global user.email "E-posta"<br>
    git config --list             # Calisma ve kullanici bilgilerini göster<br>

<br><br>

 - YEREL DEPO :
<br><br>
    git add <DOSYA(LAR)>          # Yeni ve degismis dosyalari guncellenecekler listesine ekle<br>
    git add .                     # Yeni ve degismis dosyalarin tumunu guncellenecekler listesine ekle<br>
    git add -u                    # Silinmis ve degistirilmis dosyalari guncellenecekler listesine ekle<br>
    git rm <DOSYA(LAR)>           # Calisma agacında ve dizinde dosyalari kaldir<br>
    git rm -f                     # Calisma agacında ve dizinde dosyalari zorla kaldir<br>
    git commit -m 'not'           # Değisiklikleri depoya kaydet<br>
    git commit -a -m "not"        # Tum değisiklikleri depoya kaydet<br>
    cat .gitignore                # Dosyayi depoya ekleme<br>
    git rm --cached <DOSYA>       # Dosyayi takip etmeyi birak<br>
    git diff                      # Degisiklikler arasindaki farklari goster<br>
    git diff --cached             # Listeye Eklenen Değişiklikler Arasındaki Farkları Göster<br>
    git status                    # Calisma agacindaki durumu goster<br>
    git log                       # Islem gunlugunu goster <br>

    <br><br><br>
    
 - UZAK DEPO :
 <br><br>
   git clone <ADRES>              # Uzaktaki depoyu klonla<br>
   git pull                       # Depodaki son degisiklikleri al<br>
   git push                       # Yereldeki degisiklikleri uzak depoda uygula (origin master)komutuda eklenebilir<br>
   <br><br><br>
   
   
      
 - DAL (BRANCH) KOMUTLARI :
 <br><br>
   git branch <DAL ADI>           # Dal olustur<br>
   git branch                     # Dallari goster<br>
   git checkout <DAL ADI>         # Calisilan dali degistir   <br> 
   git merge <DAL ADI>            # Dallari birlestir<br>
   git branch -d <DAL ADI>        # Dal sil<br>
 
 <br><br><br>
    
 - DIGER KOMUTLAR :
 <br><br>
   git --version                  # Git versiyon numarasını  göster<br>
   git --help                     # Git yardım sayfasını göster <br>
   git remote -v                  # Uzak depo adresini ver<br>
   git log --since=<LIMIT>        # Iki zaman araligindaki commitleri goster<br>
   git shortlog -s                # Commit yapanlarin isim ve commit sayilarini goster<br>
   git shortlog -e                # Commit yapanlarin isim ve E-postalarini goster<br>
   git shortlog -n                # Commit yapanlari commit sayisina gore sirala <br>
   git reset -- hard HEAD         # Son yapılan degisiklikleri iptal ederek HEAD geri don<br>
   git checkout -- <DOSYA>        # Sadece bir dosyayi depodaki haline geri getir<br>
   git revert HEAD                # Son yapilan commiti geri al<br>
   git stash save                 # Commit yapilmamis degisiklikleri kaydet<br>
   git stash pop                  # Commit yapilmamis degisikliklere geri don<br>
   git stash list                 # Commit yapilmamis degisiklikleri listele<br>
   git stash drop                 # Commit yapilmamis degisiklikleri kaldır<br>
   git grep                       # Mevcut dal icersinde kelime veya ifade arama<br>
   gitk                           # Git gorsellestirme programi<br>
 
 <br><br><br>
    
NOTLAR
--------
1- <DOSYA(LAR)>  yazili bolumlerde islem yapilan oge veya ogeler yazilacaktir.
2- Git ontanımlı olarak depo isimlerini origin olarak atar.

    
    
    <br><br><br>
    
KAYNAKCA
-----------

    [1] http://www.kernel.org/pub/software/scm/git/docs/
    [2] http://git-scm.com/book
    [3] https://github.com/marmara/Culture/blob/master/Git%20Komutlari


 ### Emoji Kısa Kodlarını Kullanma 


Gone camping! :tent: Be back soon.

That is so funny! :joy:
<br>
:bowtie: :bowtie:	😄 :smile:	😆 :laughing:
😊 :blush:	😃 :smiley:	☺️ :relaxed:
😏 :smirk:	😍 :heart_eyes:	😘 :kissing_heart:
😚 :kissing_closed_eyes:	😳 :flushed:	😌 :relieved:
😆 :satisfied:	😁 :grin:	😉 :wink:
😜 :stuck_out_tongue_winking_eye:	😝 :stuck_out_tongue_closed_eyes:	😀 :grinning:
😗 :kissing:	😙 :kissing_smiling_eyes:	😛 :stuck_out_tongue:
😴 :sleeping:	😟 :worried:	😦 :frowning:
😧 :anguished:	😮 :open_mouth:	😬 :grimacing:
😕 :confused:	😯 :hushed:	😑 :expressionless:
😒 :unamused:	😅 :sweat_smile:	😓 :sweat:
😥 :disappointed_relieved:	😩 :weary:	😔 :pensive:
😞 :disappointed:	😖 :confounded:	😨 :fearful:
😰 :cold_sweat:	😣 :persevere:	😢 :cry:
😭 :sob:	😂 :joy:	😲 :astonished:
😱 :scream:	:neckbeard: :neckbeard:	😫 :tired_face:
😠 :angry:	😡 :rage:	😤 :triumph:
😪 :sleepy:	😋 :yum:	😷 :mask:
😎 :sunglasses:	😵 :dizzy_face:	👿 :imp:
😈 :smiling_imp:	😐 :neutral_face:	😶 :no_mouth:
😇 :innocent:	👽 :alien:	💛 :yellow_heart:
💙 :blue_heart:	💜 :purple_heart:	❤️ :heart:
💚 :green_heart:	💔 :broken_heart:	💓 :heartbeat:
💗 :heartpulse:	💕 :two_hearts:	💞 :revolving_hearts:
💘 :cupid:	💖 :sparkling_heart:	✨ :sparkles:
⭐ :star:	🌟 :star2:	💫 :dizzy:
💥 :boom:	💥 :collision:	💢 :anger:
❗ :exclamation:	❓ :question:	❕ :grey_exclamation:
❔ :grey_question:	💤 :zzz:	💨 :dash:
💦 :sweat_drops:	🎶 :notes:	🎵 :musical_note:
🔥 :fire:	💩 :hankey:	💩 :poop:
💩 :shit:	👍 :+1:	👍 :thumbsup:
👎 :-1:	👎 :thumbsdown:	👌 :ok_hand:
👊 :punch:	👊 :facepunch:	✊ :fist:
✌️ :v:	👋 :wave:	✋ :hand:
✋ :raised_hand:	👐 :open_hands:	☝️ :point_up:
👇 :point_down:	👈 :point_left:	👉 :point_right:
🙌 :raised_hands:	🙏 :pray:	👆 :point_up_2:
👏 :clap:	💪 :muscle:	🤘 :metal:
🖕 :fu:	🚶 :walking:	🏃 :runner:
🏃 :running:	👫 :couple:	👪 :family:
👬 :two_men_holding_hands:	👭 :two_women_holding_hands:	💃 :dancer:

# Kaynak : https://www.webfx.com/tools/emoji-cheat-sheet/

<h3> Otomatik URL Bağlantısı </h3>
https://github.com/smtdeveloper or  <a href="https://www.instagram.com/smtcoder/"> instagram


 ![WhatsApp Image 2021-04-23 at 15 14 18](https://user-images.githubusercontent.com/74311713/129371447-b0bc62c1-5e7a-4827-a0b4-8aa84ca41055.jpeg)

 

<h3> <a href="https://sametakca.com/">  web sitem </a> </h3> 
 
<br> <br>
Sosyal Medya Hesaplarım 😛
<br>

<a href="https://www.instagram.com/smtcoder/">
instagram
</a>
<br>

<a href="https://www.linkedin.com/in/samet-akca-2a4bbb1a8/">
linkedin
</a>
<br>

<a href="https://www.youtube.com/channel/UCZXmqpZJ3ax5Uzm0pXeVqMg">
youtube
</a>

<br>

<a href="https://play.google.com/store/apps/developer?id=Samet+Akca&gl=TR">
Google Play
</a>
<br>
<br>

