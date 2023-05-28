Kısaca Github:
Yeni bir branch olusturmak icin :

 1) git checkout -b ibrahim(kendi adinizla)

2) Hangi branch'de oldugumuzu sorgulamak icin :
    git branch
3) GitHub.com'daki projeyi cekmek icin :
    
3.1) git checkout main ile main(ana) branchine geciyoruz.
    
3.2) git branch ile hangi branchde oldugumuzu kontrol ediyoruz. (main Branch'de olmamiz gerekiyor)
    
3.3) git fetch
    
3.4) git merge
   
3.5) git pull (Intellij'e bir kez tikladigimiz zaman  yazdiklariniz gidebilir sorun yok)
    
3.6) git checkout ibrahim ile kendi branch'imize geciyoruz. (Intellij'e bir kez tikladigimiz zaman siteden cektigimiz kodlar gidebilir sorun yok)
    
3.7) git merge main ile kodlarimi birlestiriyorum ve Intellij'de ile yazdiklarim birlesmis oldu.

4) GitHub'a kodlarimi atmak icin : (main Branch'te atmamaliyiz)
    
4.1) git checkout ibrahim kendi branch'imize gecmeliyiz.
    
4.2) git branch ile branch kontrolu
    
4.3) git add .
    
4.4) git commit -m "buraya atacagim koda not yaziyorum"
    
4.5) git push
    
4.6) --set-upstream origin ibrahimkodunu yapıştırıp çalıştır (remote da branch olusturur)
