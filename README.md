# Wake The Fuck Up

Instruktioner step-by-step.

## 1. Stora datorn -- Lägga in filer för nedladning

Gå till foldern `mixansfaith.duckdns.org > PortableGit > wake-the-fuck-up > html > downloads`

Lägg in filer du vill ska synas på webbsidan. Kom ihåg, det finns bara 16GB på SD-kortet! (Tips, lägg in torrents)

## 2. Stora datorn -- Tanka upp till GitHub

Gå till foldern `mixansfaith.duckdns.org > PortableGit` och klicka på `git-cmd`

Skriv sedan

	cd wake-the-fuck-up

När du är beredd att skicka upp dina ändringar, skriv

	git add .
	git commit -m update
	git push

Och sedan kan du stänga av git-cmd

	exit

## Tanka från GitHb till Raspberryn

Öppna PowerShell i stora ddatorn och skriv

	ssh 192.168.0.243 -l mikael

När du har kommit in skriver du

	sudo wake-the-fuck-up

Vänta tills du ser texten "Done!" skriv sedan

	exit
	exit

## Surfa

Prova surfa till `http://mixansfaith.duckdns.org`


