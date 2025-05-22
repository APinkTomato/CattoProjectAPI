# Catto project API

Aplikace backend pro Catto project
## Výpis endpointů GET:

http://localhost:9090/api/posts/getall - vypíše všechny příspěvky všech uživatelů

http://localhost:9090/api/posts/getpostsofuser/1 - vypíše všechny příspěvky jednoho uživatele

http://localhost:9090/api/posts/getpostbypostid/5 - vypíše jeden příspěvek podle id

http://localhost:9090/api/media/getall - vypíše všechny obrázky příspěvků

http://localhost:9090/api/media/getbyid/1 - vypíše obrázek příspěvku podle id

http://localhost:9090/api/users/testcredentials - testovací funkce pro ověření uživatelských údajů

http://localhost:9090/api/users/getall - vypíše všechny uživatele

http://localhost:9090/api/users/getbyusername/eliska - vypíše uživatele podlé username

## Výpis endpointů POST:

http://localhost:9090/api/posts/createorsavepost - vytvoří nový příspěvek

http://localhost:9090/api/users/createuser - vytvoří nového uživatele

http://localhost:9090/api/users/updateuser - aktualizuje údaje o uživateli

### Automatická dokumentace API
http://localhost:9090/swagger-ui/index.html