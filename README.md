# Lancement de l'application
sudo service apache2 restart

## Route

### Get movie by ID
{IP}/Symfony/SymfonyMovie/public/movie/1 

### Get all movies
{IP}/Symfony/SymfonyMovie/public/movies

### Display JSON
{IP}/Symfony/SymfonyMovie/public/displayJSON

### Get movie by slug
{IP}/Symfony/SymfonyMovie/public/movies/{slug}

### Get all routes
symfony console debug:router