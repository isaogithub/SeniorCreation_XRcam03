Connect us if you are interesting about it:
csps40608a@gmail.com
# Main programer
### Norman Hsiao
# Programer
### 林肇勳(isao)
### 遲冠宇

#Abstract
Virtual Youtuber, has been popular since 2016, Japanese virtual Youtuber [A.I.] has even create a new word [Vtuber]. As the name "virtual", the performer doesn't needs to shows up on the LIVE show, they create their own Live 2D character, some of them are not even using a human character. It makes them more different than other Youtuber or even the professional performer on TV show. Internet make anyone can be superstar, but it's sometime dangerous to became famous, but Vtuber is different, Live 2D can protect their performer even when they are b famous, they can still live like a normal person, so there is more and more performers choose to became a Vtuber .< Virtual give people more imagination, but there is more problem because they are virtual, this paper is going to talk about the problem we found and the way how we solve it.

# Function
### Zoom
【Zoom】Has been useing in cenima photography for a long time, we control the zoom in Unity virtual camera by using variable resistance and Arduino uno, can make any photographer easy to use.
Unlike the normal camera, virtual camera can zoom as long as we want without changing the lens on the camera.

![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/42707843/113886745-80484880-97f3-11eb-92c8-768499ad3ba0.gif)
### Depth Of Field
To be closer with the normal camera,we add depth of field on the virtual camera, that can make every viewer easy to recognize who is the main characters.
But there is no depth of field function on Unity 2019's camera (There is on 2018's version), so we program it by using the post-processing plug in.

![ezgif com-gif-maker (2)](https://user-images.githubusercontent.com/42707843/113887237-e92fc080-97f3-11eb-8af0-bc5bd10c9c4a.gif)
### YouTube Chat
The big problem of virtual LIVE show is there is no audience in the show, a real person can't get in to the virtual show. So we plug in the chat under the show into the stage by using YouTube stream API v3.

![ezgif com-gif-maker (3)](https://user-images.githubusercontent.com/42707843/113887447-12e8e780-97f4-11eb-8919-aaff39ad7ce5.gif)
### Camera Stabilizer
different from the expensive stabilizer, we use a C# program to filter the shake on VIVE Controller.

![ezgif com-gif-maker (4)](https://user-images.githubusercontent.com/42707843/113887646-40ce2c00-97f4-11eb-9672-d737b5fe1804.gif)
### Auto Follow
when singer are moving, the camera can follow the singer automatically, we also program the move on camera to make it work smooth.

![ezgif com-gif-maker (5)](https://user-images.githubusercontent.com/42707843/113887911-75da7e80-97f4-11eb-91c8-d7db6fe7babb.gif)
### Auto Focus
not like the troditional AF on camera build at image recognition, we catch the position from singer's forehead, so it can work more fast and stable.

![ezgif com-gif-maker (6)](https://user-images.githubusercontent.com/42707843/113888144-a5898680-97f4-11eb-8176-a71682430105.gif)
