# API
YoQuieroAyudar/JeVaisAider/IWantToHelp is a API-Driven, Charity Donation Service

We are a non-profit association that collects donations from 2 to 10 € of users of mobile app for all the organizations (associations and foundations) that participate in the program. The donations are entirely given to the organizations for which the membership is totally free.
In England IWantToHelp, in France, association Je Vais Aider, in Spain, asociación Micro Hucha Solidaria. More countries will come.
All donations are API based defined in api.yml. We are building a service to easily make donations to world charities.

- `Swagger` is for API service definition http://editor.swagger.io/
- `POS` stands for Point Of Sale. A legal entity that promotes and support us. Country specific VAT tax applies to this entity.
- `ASSO` stands for Association. A entity that receive donations.
- `USER` stands for natural user who make donations. No VAT tax applies for this entity.

Copy/paste   api.yml in swagger to read/update last API service definition

## Legal Status
- A legal non profit entity is needed to collect and redistribute donations to charities.
- Micro Hucha Solidaria is a legal non profit entity in Spain that can collect and redistribute donations.  https://microhuchasolidaria.org/en/api-3/
- Je Vais Aider is a legal non profit entity in France that can collect and redistribute donations. https://jevaisaider.org/fr/api-2/
- Ask us how to create a new legal non profit entity.

## Countries
- Micro Hucha Solidaria is the pilot project, collect and redistribute donations in Spain.
- Je Vais Aider collect and redistribute donations in France, Belgium, Swizerland,Morroco, Tunez.
- Based on the same API technology stack, more countries wil be added. German speaking countries https://twitter.com/IchWillHelfen, Italy https://twitter.com/IoVoglioAiutare, Portuguese speaking countries https://twitter.com/EQueroAjudar, UK https://twitter.com/IWantToHelpUK ...
- For each new country, we need to add country charities, translate backend messages, adapt VAT rates, adapt wallet currencies...

## API technology stack
Build on Linux Ubuntu Xenial (16.04 LTS)
- `golang`   https://github.com/golang
- `golang gin-gonic` framework for API development  https://github.com/gin-gonic/gin
- `Postgress` for database.
- `GORM` ORM library for Golang  https://github.com/jinzhu/gorm
- `Goose` for Database Migration Tool  https://bitbucket.org/liamstask/goose
- `Postman` for API testing  https://www.getpostman.com/

## Project management
- `GIT` API backend is on a private GIT.
Any Golang gopher programmer can participate for backend, any Angular 2/React for frontend. Watch, Star this page or contact-us: info@microhuchasolidaria.org ,  and we´ll contact you.

## API Status 0.15
API is still beta version. 
- `https://api.microhuchasolidaria.org/version` for Micro Hucha Solidaria.
- `https://api.jevaisaider.org/version` for Je Vais Aider.

## API total donation /metrics
Real time total donation endpoint made by all USERS
- `https://api.microhuchasolidaria.org/metrics` for Micro Hucha Solidaria.
- `https://api.jevaisaider.org/metrics` for Je Vais Aider.

## Financial API service
We use Mangopay to manage e-wallet for all entities: POS. ASSO, USERS
- `Mangopay` https://docs.mangopay.com/
- `Mangopay for Golang` Go implementation of the MangoPay HTTP REST api version 2.

## Contributions
Feel free to open an issue or create a PR.



