# Business Card Recognition using OpenCV

## 📌 PURPOSE
The purpose is that recognition of business Card using OpenCV.
Sometimes, we use recognition service for certification on mobile or web service.
However, There are various cases of recognition errors. The reason that these problems almost cause by bad quality of picture.
It makes hard to recognize the text and section of card because of brightness of light, situation where we take the pictures that is on the background that is similar to card's colors

Especially, if the card was taken on background that has a simillar color of card, It will be hard challenge us for recognition.

Thus, This is a personal project that is recognition of business card about various situation.

####       ☑️ Only recognize card section even though the taken pictures have 4 kinds of circumstances
######             1. case of easy to detect edges of card
######             2. case of the brightness of light make hard to detect card directly
######             3. case of blindness a part of card section by hands
######             4. case of the white color of card was taken on the white background

####       ☑️(+Optional) Detect the text on the business card

<br>
<br>
<br>

## 📌 METHODS
Using OpenCV, gonna detect business card about the 4 kinds of cases.
And then, I constructed the filtering algorithms along 4 kinds of cases.

- Contouring
- Binary
- Sharpen
- etc....

**(+ Optional prj.)** 
Detect a text on the detected business card

- No_sharpening
- Sharpening
- cv2.INTER_CUBIC
<br>

## 📌 RESULTS
<img src = 'https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FbkVmvS%2FbtsKbyEWtAQ%2Fb3wmkg8L2ZxdmFhG9BbBJk%2Fimg.png'>


