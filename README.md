<div align="center">
 <h3 align="center">Nginx Docker Static Content</h3>
 <hr>

 <p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c5/Nginx_logo.svg/250px-Nginx_logo.svg.png" />
 </p>
</div>


This repository contains a docker container with nginx server for to serving static content

[Docs](https://docs.nginx.com/nginx/admin-guide/web-server/serving-static-content/)

## Usage

1. Create container
  
       $ docker-compose -f docker-compose.yml up
  
2. For check install go to `<ip o localhost>` in your browser

3. Add content in path `/www/data/`

4. In your browser go to `<ip or localhost>/data`

