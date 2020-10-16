# 음악 장르 분류기

<li>원본 데이터<a href="https://www.kaggle.com/andradaolteanu/gtzan-dataset-music-genre-classification?">[CLICK]</a></li>

<br/>

### 사용한 데이터
<li>blues, classical, country, disco, hiphop, jazz, metal, pop, reggae, rock 총 10가지 장르의 음악파일</li>
<li>각각의 장르마다 30초 길이의 100개의 음악파일</li>

### Data Preprocessing
<li> 제공된 원본 데이터는 Mel Spectrograms을 사용하여 오디오를 시각화.</li>
<li> 실제 프로젝트에서는 MFCC를 사용하여 오디오를 시각화</li>
<li> train/test data를 8:2 비율로 나누기
  <a href="https://github.com/LeeSangMin96/music_classification/tree/master/train">[TRAIN]</a>
  <a href="https://github.com/LeeSangMin96/music_classification/tree/master/test">[TEST]</a>
</li>
<li> blues:0, classical:1, country:2, disco:3, hipho:4, jazz:5, metal:6, pop:7, reggae:8, rock:9 으로 라벨링</li>
