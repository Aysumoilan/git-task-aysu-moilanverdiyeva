# Git ve GitHub Praktiki Tapşırıq

## Şəxsi Məlumatlar
* **Ad, Soyad:** Aysu Moilanverdiyeva
* **Qrup:** 845i

## Layihənin Qısa İzahı
Bu layihə Git versiya idarəetmə sisteminin və GitHub platformasının əsas funksionallığını praktiki tətbiq etmək üçün hazırlanmışdır. Layihə çərçivəsində təməl veb səhifə (HTML) və istifadəçi ilə qarşılıqlı əlaqədə olan sadə Python proqramı işlənilmişdir.

## Layihədə Olan Fayllar
* `index.html` — İstifadəçi haqqında məlumatları və təməl CSS üslublarını əks etdirən HTML səhifəsi.
* `app.py` — İstifadəçidən ad və yaş daxil etməsini istəyən və müvafiq salamlaşma mesajı çıxaran Python proqramı.
* `README.md` — Layihə strukturu və istifadə olunan komandalar haqqında ətraflı məlumat sənədi.

## İş Axını (Workflow) və Branch Strateqiyası
1. Əsas kod bazası `main` branch-ında yaradılmışdır.
2. HTML dəyişiklikləri üçün `feature-html` branch-ı açılmış, yeniləmələr tamamlandıqdan sonra `main` ilə birləşdirilmişdir (merge).
3. Python proqramının inkişafı üçün `feature-python` branch-ı açılmış və tamamlandıqdan sonra `main` branch-ına daxil edilmişdir.

## İstifadə Olunan Əsas Git Komandaları
* `git init` — Yeni lokal repository başlatmaq üçün.
* `git status` — İş sahəsindəki və staging zonasındakı dəyişiklikləri izləmək üçün.
* `git add <fayl>` — Dəyişiklikləri staging sahəsinə əlavə etmək üçün.
* `git commit -m "mesaj"` — Dəyişiklikləri məntiqli mesajla yaddaşda saxlamaq üçün.
* `git log --oneline` — Commit keçmişini qısa xronoloji formada görmək üçün.
* `git branch` — Mövcud branch-ların siyahısını çıxarmaq üçün.
* `git switch -c <branch_adı>` — Yeni branch yaradıb dərhal ona keçmək üçün.
* `git merge <branch_adı>` — Başqa bir branch-dakı dəyişiklikləri cari branch-a birləşdirmək üçün.
* `git push -u origin <branch_adı>` — Lokal commit-ləri distant (GitHub) repository-yə yükləmək üçün.