create repo [final]
in car1 --- git clone the repo
cp -r duckietown final/duckietown
cd final/duckietown
rm -rf .git
cd ~/final
git add .
git commit -m "XXX"
git push -u origin master

in car2 ---> git clone the repo
combine two codes
git add .
git commit -m "XXX"
git push -u origin master

in car1 --> cd final
git pull   (update code)
