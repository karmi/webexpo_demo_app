= Ukázková aplikace pro přednášku "Efektivní vývoj webových aplikací v Ruby on Rails"

== O aplikaci

Aplikace obsahuje jednoduchý "plánovač", inspirovaný aplikací http://www.tadalist.com/

Přes svoji jednoduchost demostruje doporučené postupy a techniky vývoje moderní webové
aplikace v Ruby On Rails.


== Požadavky na instalaci

* Programovací jazyk Ruby (http://www.ruby-lang.org/en/downloads/)
* Balíčkovací systém Rubygems (http://www.rubygems.org)
* Framework Ruby On Rails (http://rubyonrails.org/down)
* Databázi SQLite (výchozí) nebo MySQL


== Instalace

* Na příkazovém řádku se přepněte do adresáře s aplikací
* Chcete-li namísto SQLite použít MySQL, přejmenujte soubor `config/database.mysql.yml` na `config/database.yml`
* Vytvořte databáze příkazem `rake db:create:all`
* Vytvořte databázové schéma příkazem `rake db:migrate`
* Načtěte testovací data do databáze příkazem `rake db:fixtures:load` (nepovinné)
* Spusťte aplikační server příkazem `ruby script/server`
* Otevřete aplikaci v prohlížeči na adrese http://localhost:3000/


(c) 2008 Karel Minařík, www.karmi.cz. Released under the MIT license.