## जन्मदिन का कार्ड बनाना

अपना स्वयं का जन्मदिन का कार्ड बनाने के लिए HTML और CSS के बारे में सीखी गई बातों का उपयोग करें।

+ [यह ट्रिंकेट](http://jumpto.cc/web-card){:target="_blank"} खोलें।

हमने आपके द्वारा आरंभ करने के लिए बहुत-से कोड लिखे हैं, परन्तु अभी तक जन्मदिन का कार्ड काफ़ी फालतू लगता है, इसलिए आप HTML और CSS कोड में कुछ परिवर्तन करेंगे।

+ कार्ड के सामने की ओर बटन पर क्लिक करें, और आप देखेंगे कि इसके अंदर की चीज़ें दिखाने के लिए यह खुल जाता है।

![screenshot](images/birthday-click.png)

+ HTML कोड की लाइन 14 पर जाएँ। अपना कार्ड कस्टमाइज़ करने के लिए टेक्स्ट संपादित करने का प्रयास करें।

![screenshot](images/birthday-card-html.png)

+ क्या आप रोबोट के छवि के लिए HTML कोड ढूँढ़ सकते हैं, और `robot` शब्द को `sun` में परिवर्तित कर सकते हैं?

--- hints ---
--- hint ---
+ कोड खोजने के लिए लाइन 17 देखें।
+ `robot` शब्द को `sun` में परिवर्तित करें, और आप देखेंगे कि छवि बदल गई है!

![screenshot](images/birthday-card-sun.png)
--- /hint ---
--- /hints ---

आप जन्मदिन के कार्ड के लिए `boy` (लड़का), `diamond` (हीरा), `dinosaur` (डायनोसोर), `flowers` (फूर), `girl` (लड़की), `rainbow` (इंद्रधनुष), `robot` (रोबोट), `spaceship` (अंतरिक्ष यान), `sun` (सूर्य), `tea` (चाय), या `trophy` (ट्रॉफ़ी) में से किसी भी शब्द, या यदि आप क्रिसमस कार्ड बनाना चाहें, तो `cracker` (पटाखा), `elf` (बौना), `penguin` (पेंगुइन), `present` (उपहार), `reindeer` (बारहसिंगा), `santa` (सांता), या `snowman` (हिम मानव) में से किसी भी शब्द का उपयोग कर सकते हैं।

आप जन्मदिन के कार्ड के CSS कोड को संपादित भी कर सकते हैं।

+ `style.css` के लिए टैब पर क्लिक करें। प्रथम पूर्ण भाग कार्ड के **outside** के लिए CSS स्टाइल का हो सकता है।

+ `background-color` को `lightgreen` में परिवर्तित करें।

![screenshot](images/birthday-card-outside.png)

+ आपके छवि के आकार में परिवर्तन भी कर सकते हैं। `#outside-pic` CSS कोड पर जाएँ, और बाहरी छवि की `width` (चौड़ाई) और `height` (ऊँचाई) को `200px` (`px` का मतलब पिक्सल है) में बदलें।

![screenshot](images/birthday-card-size.png)

+ फॉन्ट को भी बदला जा सकता है। `#outside-title` CSS पर जाएँ और `font-family` को `Comic Sans MS` में बदलें और `font-size` को `16pt` में बदलें।

![screenshot](images/birthday-card-font.png)

आप अन्य फोंट्स का उपयोग कर सकते हैं, उदाहरण के लिए:
+ `<span style="font-family: Arial;">arial</span>`
+ `<span style="font-family: impact;">Impact</span>`
+ `<span style="font-family: tahoma;">Tahoma</span>`
