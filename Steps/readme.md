git clone git@github.com:ONFoundation/on-brand.git
cd on-brand/
git remote rm origin
git remote add origin git@github.com:The-Open-Network/on-brand.git
git config --global user.email "your@email.tld"
git config --global user.name "Your Name"
git push --set-upstream origin master
