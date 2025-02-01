<h1 align="left">Hey 👋 What's up?</h1>

###

<p align="left">My name is ... and I'm a ..., from ....</p>

###

<h2 align="left">Git kurulumu ve yapılandırma</h2>

###

<p align="left">git config --global user.name "senaydn"<br>git config --global user.email senaaydin04@gmail.com</p>

###

<h2 align="left">Git temel komutları (init, add, commit, status, log)</h2>

###

<p align="left">git init: Yeni bir Git repository'si oluşturur.<br>git add <dosya_adı>: Dosyaları staging alanına ekler.<br>git commit -m "Mesaj": Staging alanındaki değişiklikleri commit eder.<br>git status: Çalışma dizinindeki değişikliklerin durumunu gösterir.<br>git log: Yapılan commit'lerin geçmişini gösterir.</p>

###

<h2 align="left">Basit bir Git repository oluşturma ve commit işlemleri</h2>

###

<p align="left">•	Yeni bir Git repository'si oluşturmak için:<br>git init<br>•	Değişiklik yapıldıktan sonra bu dosyayı eklemek ve commit etmek için:<br>git add <dosya_adı><br>git commit -m "İlk commit mesajı"</p>

###

<h2 align="left">GitHub ile yerel repo bağlantısı (git remote, git push, git pull)</h2>

###

<p align="left">•	git remote: Yerel repository’yi uzak repository ile ilişkilendirir.<br>git remote add origin <repository_URL><br>•	git push: Yerel repository’deki değişiklikleri GitHub’daki uzak repository’ye gönderir.<br>git push -u origin master<br>•	git pull: GitHub’daki uzak repository’den yerel repository’ye değişiklikleri çeker.<br>git pull origin master<br><br>git clone <repository_URL></p>

###

<h2 align="left">Branching ve merging (git branch, git checkout, git merge)</h2>

###

<p align="left">•	git branch: Yeni bir dal (branch) oluşturur veya mevcut dalları listeler.<br>•	git checkout: Başka bir dala geçmek veya bir dalı oluşturmak için kullanılır.<br>Örnek:<br>git checkout -b <branch_adı><br>•	git merge: İki dalı birleştirir. Örneğin, bir özelliği geliştirdiğiniz bir dalı ana dala (main/master) birleştirmek için kullanılır.</p>

###

<h2 align="left">Rebase ve Cherry-pick kullanımı</h2>

###

<p align="left">•	Rebase: Bir dalı başka bir dalın üzerine taşıyarak, geçmiş commit'lerinizi yeniden düzenler. Bu, daha temiz bir commit geçmişi sağlar.<br>Örnek:<br>git rebase <branch_adı><br>•	Cherry-pick: Belirli bir commit'i başka bir dala uygular. Yani, sadece istediğiniz commit'i seçip alabilirsiniz.<br>Örnek:<br>git cherry-pick <commit_hash></p>

###

<h2 align="left">Git Reset ve Revert ile değişiklik yönetimi</h2>

###

<p align="left">•	git reset: Commit geçmişini geri alır ve dosya durumlarını (staging area veya çalışma dizini) belirttiğiniz noktaya sıfırlar.<br>Örnek:<br>git reset --hard (ya da --soft) <commit_hash><br>•	git revert: Bir commit'in yaptığı değişiklikleri geri alır, ancak commit geçmişini değiştirmez. Yeni bir commit oluşturur.</p>

###

<h2 align="left">Git Stash ile geçici değişiklikleri kaydetme</h2>

###

<p align="left">•	git stash: Çalışma dizinindeki değişiklikleri geçici olarak kaydeder ve çalışma dizinini temizler. Daha sonra bu değişiklikleri geri alabilirsiniz.<br>Örnek:<br>git stash<br>git stash pop</p>

###

<h2 align="left">Kendi projenizi oluşturup GitHub’da paylaşma</h2>

###

<p align="left">Adımlar:<br>git init<br>git add .<br>git commit -m "İlk commit"<br>git remote add origin <repository_URL><br>git push -u origin master</p>

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="javascript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="40" alt="typescript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="40" alt="react logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" height="40" alt="nextjs logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/storybook/storybook-original.svg" height="40" alt="storybook logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="40" alt="nodejs logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nestjs/nestjs-original.svg" height="40" alt="nestjs logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jest/jest-plain.svg" height="40" alt="jest logo"  />
</div>

###
