# Company

rm -rf .git  
git init  
git add .  
git commit -m "first commit"  


## Netlify
https://github.com/netlify/netlify-plugin-nextjs/#readme  


cd web  
touch netlyfy.toml  
npm install -D @netlify/plugin-nextjs@latest  


...then add the plugin to your netlify.toml file:  
[[plugins]]  
package = "@netlify/plugin-nextjs"  

[build]  
publish = ".next"  

base:  
web

build:     
npm run build  


## examples:
https://insp.ngo/  
https://www.realchangenews.org/

## todo
[] colors  
  red  
  orange  
[] make todo  
[] sitemap  
  - [] nav
    - [] donate
    - [] social links
    - [] quick links
    - [] 
 - [] pages
   - []index
     - [] hero     
     - [] places to go on the site     
     - [] make it look like a news site?
   - []
- [] footer     