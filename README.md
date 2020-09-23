# ASLR on the line - fancut

Erik Bosman (@brainsmoke) gave [a talk at the ccc](https://www.youtube.com/watch?v=ewe3-mUku94).
And got some rude comments on youtube about the way he presented. So I spend some time to cut out the "uhms" and some long pauses.
To make the talk easier to follow and direct the attention from the way of presenting to the content of the presentation.


It is still a work in progress but if its finish I will upload it to youtube and share a link here.

### setup
```
adduser chiller
su chiller
cd ~/Videos
git clone https://github.com/chillermovies/fancut_ASLR_on_the_line

mkdir -p mov
cd mov
wget https://cdn.media.ccc.de/congress/2017/h264-hd/34c3-9135-eng-deu-ASLR_on_the_line_hd.mp4
cd ..
kdenlive aslr.kdenlive
```

