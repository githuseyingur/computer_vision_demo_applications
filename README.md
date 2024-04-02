## FACE RECOGNITION WITH ARCFACE
This repo contains notes from the 'Bilgisayarlı Görü Uygulama Alanları(Computer Vision Application Areas)' course on BTK Akademi.

- Only a part of the MS1M dataset was used : **[DATASET & FILES](https://drive.google.com/file/d/1wjA5Gtx6EnH9W4m9gbFwzkBUWjceFqT3/view?usp=sharing)**

  

### SOTA : the State Of The Art
- Working with the complete MS1M dataset
- conf.mode = 'ir'
- conf.depth = '100'
- conf.total_epoch = 20
- conf.milestones = [12,16,18]

lfw = gives an accuracy of 99.83%. (is the best rate ever obtained.) <br>
It takes 5 days with two v100(32GB).
