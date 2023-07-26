## రంగులు!

మీ రెసిపీ వెబ్‌పేజీకి కొన్ని రంగులను జోడిద్దాం.

+ మీ వెబ్‌పేజీకి రంగులను ఎలా జోడించాలో మీరు ఇప్పటికే నేర్చుకున్నారు. వెబ్‌సైట్ బాడీలోని అన్ని వచనాలను నీలం రంగులోకి మార్చడానికి మీరు ` style.css ` ఫైల్ లో ఈ కోడ్‌ను జోడించండి 

    body {
        color: blue;
    }
    

![స్క్రీన్ షాట్](images/recipe-blue.png)

+ మీ బ్రౌజర్‌కు ` నీలం ` , ` పసుపు ` మరియు ` లైట్‌గ్రీన్ ` వంటి రంగులు తెలుసు , కానీ మీ బ్రౌజర్‌కు వాస్తవానికి ** పేర్లు ** 140 కి పైగా వివిధ రంగులు తెలుసు అని మీకు తెలుసా?

మీరు ఉపయోగించగల అన్ని రంగు పేర్ల జాబితా [ jumpto.cc/colours ](http://jumpto.cc/colours) లో ఉంది: ` టమోటా` , ` ఫైర్‌బ్రిక్ ` మరియు ` పీచ్‌పఫ్ ` వంటి రంగు పేర్లు ఉంటాయి

` నీలం` నుండి వచన రంగును ` టమోటాకు ` మార్చండి

![స్క్రీన్ షాట్](images/recipe-tomato.png)

+ మీ బ్రౌజర్‌కు 140 రంగుల పేర్లు తెలుసు, కానీ వాస్తవానికి ** రంగు విలువలు ** 16 మిలియన్ల కంటే ఎక్కువ రంగుల విలువలు తెలుసు!

బ్రౌజర్‌కు ఏ రంగును ప్రదర్శించాలో చెప్పడానికి, మీరు ఎంత ఎరుపు, ఆకుపచ్చ మరియు నీలం ఉపయోగించాలో తెలియజేయాలి.

ఎరుపు, ఆకుపచ్చ మరియు నీలం మొత్తాలను `0` మరియు ` 255 ` మధ్య సంఖ్యగా వ్రాస్తారు.

![స్క్రీన్ షాట్](images/recipe-rgb-img.png)

లేత పసుపు నేపథ్యాన్ని ప్రదర్శించడానికి వెబ్‌పేజీ లోని ఈ కోడ్‌ను CSS కు జోడించండి:

    నేపథ్యం: rgb (250,250,210);
    

![స్క్రీన్ షాట్](images/recipe-rgb.png)

+ మీరు కావాలనుకుంటే, హెక్సాడెసిమల్ కోడ్ (లేదా ** హెక్స్ కోడ్ **) ఉపయోగించి ఏ రంగును ప్రదర్శించాలో బ్రౌజర్‌కు తెలియజేయవచ్చు. హెక్స్ సంకేతాలు ఎల్లప్పుడూ `#` తో ప్రారంభమవుతాయి, `00` మరియు `ff` మధ్య హెక్సాడెసిమల్ 'సంఖ్యలను' ఎరుపు, ఆకుపచ్చ మరియు నీలం ర౦గు మొత్తానికి ఉపయోగించాలి. ఇది పైన ఉన్న కోడ్ ` rgb()` కు సమానమైన రీతిలో పనిచేస్తుంది.

![స్క్రీన్ షాట్](images/recipe-hex-img.png)

మీ CSS లో కోడ్ ను ` rgb()` ఈ హెక్స్ కోడ్‌తో మార్చండి:

    నేపథ్యం: #fafad2;
    

![స్క్రీన్ షాట్](images/recipe-hex.png)

మీరు మునుపటిలాగే లేత పసుపు రంగును చూడాలి!