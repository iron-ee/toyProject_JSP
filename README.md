
# Toy Project - JSP로 서버프로그램 구현

</br>
</br>

## 모방해 볼 사이트의 대략적인 page

</br>

### 메인 page

##### 메인 page 구현 예정

- 상단에 최신앨범은 그대로 유지하고   
하단에는 인기차트를 좀 더 넓게 펼칠 예정

</br>

- 추상적 모델 : music

<img src="img/main_page.png" width="800px" height="1000px"></img>

</br>
</br>

### 회원가입 page

##### 회원가입 page 구현 예정

- username, password, nickname, phone, email 을 입력 받도록 디자인 할 예정

</br>

- 추상적 모델 : user

<img src="img/join_page.png" width="600px" height="800px"></img>

</br>
</br>

### 로그인 page

- 일단 username, password를 입력 받아 로그인 할 예정   
(추후 변경 될 수도 있습니다.)

</br>

- 추상적 모델 : user

<img src="img/login_page.png" width="600px" height="800px"></img>

</br>
</br>

### 인기차트 page

##### 인기차트 page 구현 예정

- albumImg, songTitle, singer, albumTitle, songLike 를 표시할 예정
- 곡 제목 또는 앨범명을 클릭하면 앨범 정보로 들어가게 할 예정
- 스트리밍은 audio 태그를 이용 할 예정
- songLike 수에 따라서 순위를 변경 할 예정

</br>

- 추상적 모델 : music

<img src="img/popular_chart.png" width="800px" height="1000px"></img>

</br>
</br>

### 최신음악 page

##### 최신음악 page 구현 예정

- 인기차트와 동일하게 만들 예정
- albumDate 날짜에 따라서 순서를 변경 할 예정

</br>

- 추상적 모델 : music

<img src="img/new_song.png" width="800px" height="1000px"></img>

</br>
</br>

### 최신앨범 page

##### 최신앨범 page 구현 예정

- albumImg, albumTitle, singer, albumDate 를 표시할 예정
- 앨범 사진 또는 제목을 클릭하면 앨범 정보로 들어가게 할 예정
- albumDate 날짜에 따라서 순서를 변경 할 예정

</br>

- 추상적 모델 : music

<img src="img/new_album.png" width="800px" height="1000px"></img>

</br>
</br>

### 앨범정보 page

##### 앨범정보 page 구현 예정

- albumImg, albumTitle, singer, albumDate, category, entertainment 를 표시할 예정
- 수록곡에는 albumId 값을 찾아서 동일한 key 값으로 표시할 예정
- 하단에는 댓글을 만들 예정

</br>

- 추상적 모델 : music, reply

<img src="img/album_info.png" width="800px" height="1000px"></img>

<img src="img/album_reply.png" width="800px" height="1000px"></img>

</br>
</br>

### 최신뮤비 page

##### 최신뮤비 page 구현 예정

- videoImg, videoTitle, singer, videoDate 를 표시할 예정
- 이미지 또는 제목을 클릭하면 뮤비 정보로 들어가게 할 예정

</br>

- 추상적 모델 : video

<img src="img/new_movie.png" width="800px" height="1000px"></img>

### 뮤비정보 page

##### 뮤비정보 page 구현 예정

- ifram 태그를 사용하여 동영상을 표시할 예정

</br>

- 추상적 모델 : video

<img src="img/movie_info.png" width="800px" height="1000px"></img>


</br>

### 검색 page

##### 검색 page 구현 예정

- songTitle, albumTitle, singer 를 검색하는 페이지

</br>

- 추상적 모델 : music

<img src="img/search_song.png" width="800px" height="1000px"></img>