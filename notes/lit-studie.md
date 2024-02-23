### Train VUB corpus
Speech-to-text, also known as Speech Recognition, is a tech-
nology that is able to recognize and transcribe spoken language into text. In subsequent steps, this transcription can be used to complete a multitude of tasks, such as providing automatic subtitles or parsing voice commands

Started with DeepSpeech 

The ﬁeld of Artiﬁcial Intelligence has managed to achieve unprecedented re-sults in the last couple of decades, across many ﬁelds, ranging from computer vision, e.g., beating human performance at the image recognition task, to reinforcement learning, e.g., achieving superhuman performance at the game of Go.

This work will take a closer look at another one of these ﬁelds, namely Speech-to-Text (STT), otherwise referred to as Speech Recognition (SR). Simply put, speech-to-text is the ability of a machine to “hear” spoken language and transcribe it

STT as a ﬁeld has many other practical applications, ranging from health-care and helping people with disabilities , to controlling military aircrafts. This potential societal impact makes STT an attractive research sub-
ject. 

for the future , This includes developing further techniques for handling noisy data, but also including other smaller datasets such at the one available through the Common Voice project. We are also interested in developing diﬀerent neural architectures and also using other frameworks such as PyTorch-Kaldi for this task.

### Malayalam speech to text
Speech is considered as the one of I. the common modes of communication among human beings in the 
modern civilized societies and it is the most natural and efficient way of exchanging information. It encourages numerous applications which includes a helping hand 
for illiterate individuals, support of telephonic directories, supervision gadgets for updating the health status in 
hospitals, in industrial banking sector etc. 

### deep learning approach for speech recognition
there are some languages or words that humans cannot easily
interpret, read, or decode to comprehend. As a result, it is critical to design and builds a
system that can analyze, comprehend, and generate human languages from given text. So, to
work on it, speech and language processing research allow computers to understand statements
written or spoken in human or natural languages

### multilangual speech tot text using deep learning
Current text and speech recognition and translation methods have a very low accuracy in 
translating sentences which contain a mixture of two or more different languages. The paper proposes a 
novel approach to tackling this problem and highlights some of the drawbacks of current recognition and 
translation methods. 

Multilingual translation and recognition is an important problem to tackle as there is a tendency for people 
to speak in a mixture of languages. By solving this problem, the barrier of language and communication 
can be lifted and thus can help people connect better and more comfortably with each other. 
-> the same idea can be applied to any language and their dialects
The general problems we need to tackle:
1. Recognizing that the sentence is a mixture of two or more languages

A popular speech and text recognition tool is the google api.
When using such API's the performance relies heavily on the language you are using. -> it will always try to map a word to the one that sounds the most similar in the language it is trained on.

### Development of the Speech-to-Text Chatbot Interface 
New speech recognition technologies and methods will become a central part of future life because they save a lot of communication time, replacing common texting with voice/audio.

### using speech to text tech to empower young people with special needs
As we can see in this study STT technology can also be used to help children with difficulties in spoken and written communication. The results showed that this approach
had boosted the quantity and quality of handwritten text, with post-test screen-written text significantly
better than handwritten at post-test. The self-esteem instrument also showed positive and statistically
significant results.
Writing difficulties are among the most common learning issues, affecting up to 15% of the school-age
population, and children who fail to develop developmentally appropriate writing skills are at a significant
disadvantage 
 using speech-to-text
(STT) technology may offer a means of circumventing transcriptional difficulties; children are able to
dictate, edit and review their work using voice commands as well as typing. The use of such systems is
intended not only to improve the quality and quantity of students’ communication of thoughts and ideas on
to a screen, but also to transfer this improvement to writing on paper.


### Applications in Healthcare:

The article highlights that speech-to-text conversion technology offers significant benefits in the healthcare sector. It emphasizes that this technology can reduce the time and cost of recording information in medical records.
Challenges in Medical Documentation:

The article discusses the limitations of traditional written documentation in healthcare, including issues like improper registration of data, illegibility, and invalid data. These limitations compromise the quality of medical records and can have serious consequences, such as documentation errors leading to patient harm.
Speech Recognition Technology's Role:

Speech recognition technology, as discussed in the article, addresses these challenges by providing an alternative means of documenting patient data. It allows healthcare providers, including doctors, to communicate with computer systems easily, reducing the need for manual transcription.
Efficiency and Cost-Effectiveness:

The article emphasizes that speech recognition technology can significantly reduce the time needed to complete medical records, leading to improved productivity and reduced documentation costs. This has a positive impact on healthcare services' efficiency and the quality of patient care.
Acceptance and Challenges:

The article also acknowledges that there are challenges to the implementation of speech recognition technology in healthcare. Acceptance by healthcare providers, especially doctors, can be a potential barrier. Additionally, environmental factors, such as noise pollution, can affect the quality of sound recordings.
Future Prospects:

The article suggests that speech recognition algorithms and clinical vocabulary are expected to improve in the future, allowing the technology to understand natural languages better and make dictation more structured and efficient.
Incorporating these points into your literature study will provide insights into the application of speech recognition technology in healthcare, its benefits, and the challenges it faces. This can be a valuable addition to your research paper's discussion on STT technology's impact on healthcare.

### Bias in flemish automatic speech recognition
Research has shown that automatic speech recognition (ASR) systems
exhibit biases against different speaker groups, e.g., based on age or gender. Seeing as Belgian Dutch, which is also known as Flemish, is often not included in Dutch ASR systems, a state-of-the-art ASR system for Dutch is trained using the Netherlandic Dutch data from the Spoken Dutch Corpus. Using the Flemish data from the JASMIN-CGN corpus.

The research conﬁrms a bias against speakers from West
Flanders and Limburg, as well as against children, male speakers, and non-native
speakers.

It demonstrated that an ASR trained on Netherlandic (NL) Dutch performed poorly on Flemish, Dutch spoken in Belgium, while Van Dyck et al.[10] found low word error rates (WERs) for Flemish in a Flemish-trained model, namely approximately 10%. Since most (commercial) ASR systems do not include Flemish [11], and
Flemish speakers thus have to use NL Dutch ASR systems, and since flemish consists of various regional varieties that differ in intelligibility.

we showed that a state-of-the-art Dutch ASR
system has biases against West Flemish, Limburgish, young, male, and non-native speakers.

For instance Garnerin et al. [28] found that an imbalanced corpus performed better for male speakers, whereas Adda-Decker and Lamel [29] obtained better recognition for female speakers in a balanced corpus.

Further research could thus include a larger dataset or more recent architectures as well as bias mitigation techniques.


### Automatic Speech Recognition and Pronunciation Error Detection of Dutch Non-native Speech: cumulating speech resources in a pluricentric language.

The shortage of large-scale learners’ speech corpora and precise manual annotations are two major challenges for 
automatic L2 speech recognition and error detection in L2 speech, especially for non-dominant varieties of 
pluricentric languages.

Conclusion, The Flemish Dutch learners’ ASR model can be 
improved by cumulating the Netherlandic Dutch and Flemish Dutch 
datasets. Second, the transfer learning-based model can effectively 
transfer the Netherlandic Dutch knowledge to promote the Flemish 
Dutch learners’ ASR mode, but interference problems may arise, and its performance is far from impressive.


### A hybrid ASR System for southern dutch

In this work, we implemented a state-of-the-art hybrid system for Southern Dutch. For the acoustic model, we train a HMM-DNN on 155 hrs of the Corpus Gesproken
Nederlands (CGN) with a rather standard Kaldi recipe.

We augment the training data by applying speed and volume perturbations (Ko et al. 2015, Rath
et al. 2013). Both augmentation methods result in mean shifts in the MFCC domain, similar to
vocal tract length normalisation. Speed perturbation is achieved by resampling the audio with speed
factors 0.9, 1.0 and 1.1, effectively tripling the training data.

For volume perturbations, audio is
scaled by a factor drawn from a uniform distribution [81 , 2].


### Towards inclusive automatic speech recognition
Practice and recent evidence show that state-of-the-art (SotA) automatic speech recognition
(ASR) systems do not perform equally well for all speaker groups. Many factors can cause this
bias against different speaker groups.
The results show that only a
fraction of the bias can be explained by pronunciation differences between speaker groups, and
that in order to mitigate bias, language- and architecture specific solutions need to be found.


### huidige inleiding 

Nieuwe spraakherkenningstechnologieën
en -methodes zullen een centraal onderdeel
worden van het toekomstige leven omdat
ze veel communicatietijd besparen en het
gewone sms’en vervangen door
spraak/audio.
Shakhovska e.a., 2019
In het bovenstaande voorbeeld wordt duide-
lijk geïllustreerd hoe belangrijk speech-to-text is
in ons dagelijks leven, zowel in het nu als in de toe-
komst. Deze technologie speelt een steeds gro-
tere rol in onze snel evoluerende wereld doordat
het ons in staat stelt gesproken taal nauwkeurig
om te zetten in geschreven tekst. Tegenwoordig
wordt spraak-naar-tekst al toegepast in diverse
toepassingsgebieden, zoals:
• kinderen helpen met problemen in gespro-
ken, geschreven communicatie (Kambouri
e.a., 2023).
• automatische ondertiteling.
• Google assistant, Siri.
In dit onderzoek ligt de focus voornamelijk op
spraakopdrachten en regionale accenten, zoals
die in gesprekken tussen oudere personen en stu-
denten van HOGENT (bijvoorbeeld van de oplei-
ding verpleegkunde) voorkomen. We vragen ons
af of de verwerking van regionale accenten een
uitdaging vormt voor deze technologieën, gezien
de aanzienlijke vooruitgang die ze hebben ge-
boekt. Het leeftijdsverschil tussen de bellers en
deelnemers aan het onderzoek kan hierbij een in-
teressant aspect vormen dat invloed heeft op de
transcriptiekwaliteit.
1.1. Probleemstelling
In het Nederlandse taalgebied manifesteert
zich een uitgebreide variatie en diversiteit aan re-
gionale accenten zoals ook aangekaart in het on-
derzoek van (Ghyselen e.a., 2020) en (Barbiers &
Bennis, 2004). Deze diversiteit vormt mogelijk
een uitdaging voor speech-to-text systemen die
oorspronkelijk zijn getraind op standaard Neder-
lands. Onze centrale vraag luidt: Kan deze tech-
nologie de variatie en diversiteit begrijpen en kan
ze verbeterd worden om nauwkeurige transcrip-
ties te leveren voor (niet-standaard) Nederlands?
Deze vraag zal de kern vormen van ons onderzoek
en zal dienen als leidraad.
Daarbij streven we naar de volgende meetbare
deelvragen:
• Wat is de invloed van omgevingsgeluid op
de kwaliteit van speech-to-text? (gemeten
aan de hand van word error rate)
• Hoe bruikbaar zijn modellen die getraind zijn
op andere talen, voor Nederlands?
Deze deelvragen leiden tot volgende doel-
stelling: Het verbeteren van een model dat
bruikbaar is voor (niet-standaard) Nederlands.
• Hoe presteert het verbeterde model op woor-
den die niet behoren tot de standaardtaal?
Aan de hand van bovenstaande deelvraag
kunnen we de volgende doelstelling beant-
woorden: Het model moet een goede word
error rate hebben voor woorden die niet be-
horen tot de standaardtaal.
• Welke open en closed-source modellen pres-
teren het beste voor Nederlands?
• Is het model te oud om nog bruikbare resul-
taten te leveren?
• Hoe snel kan het model in productie worden
gebruikt?
Bovenstaande vragen helpen ons volgende
doelstelling te beantwoorden: Identificeren
van bruikbare open en closed-source model-
len voor Nederlands.
Vanuit het bovenstaande idee is het doel ont-
staan om te onderzoeken of we bruikbare trans-
criptie kunnen bereiken voor regionale accenten
en (niet-standaard) Nederlands. Daarnaast wil-
len we de spreker identificeren, aangezien leeftijd
ook invloed kan hebben op de resultaten. Als het
resultaat niet overeenkomt met onze verwachtin-
gen, streven we toch naar inzichten en een nut-
tige bijdrage.
Het concrete resultaat zal bestaan uit een (aan-
gepast) model voor spraakherkenning dat geop-
timaliseerd is voor (niet-standaard) Nederlands.
In het geval dat het ontwikkelen of aanpassen van
een dergelijk model niet succesvol blijkt te zijn, zal
het onderzoeksrapport een gedetailleerde evalu-
atie bevatten van de uitdagingen en beperkingen
die zijn geïdentificeerd.
1.2. Opzet van het onderzoek
Dit onderzoek zal worden uitgevoerd in ver-
schillende fasen, beginnend met een literatuur-
studie om inzicht te krijgen in de huidige stand
van zaken binnen het vakgebied. Vervolgens zul-
len we de methodologie beschrijven, waarbij ex-
pliciet aandacht wordt besteed aan de bruikbaar-
heid voor gesprekken tussen oudere personen en
studenten van HOGENT. Hierbij zullen we onze
aanpak voor het verkennen en verbeteren van de
transcriptiekwaliteit in detail uiteenzetten. Ten
slotte zullen we de verwachte resultaten bespre-
ken.



### nieuwe inleiding
Inleiding
Spraak-naar-tekst technologie, ook bekend als Spraakherkenning (SR), is een integraal onderdeel geworden van ons dagelijks leven en biedt de mogelijkheid om gesproken taal om te zetten in tekst. Met de vooruitgang in kunstmatige intelligentie (AI), met name op het gebied van deep learning, hebben SR-systemen een opmerkelijke nauwkeurigheid en functionaliteit bereikt, waardoor een breed scala aan toepassingen mogelijk is geworden, zoals automatische ondertiteling en parsing van spraakopdrachten (Train VUB corpus).

Context en achtergrond
Dit onderzoek richt zich op Speech-to-Text (STT) technologie om de praktische toepassingen en mogelijke maatschappelijke gevolgen te onderzoeken. Het belang en de relevantie van STT in de huidige samenleving worden onderstreept door zijn uitgebreide toepassingen, die variëren van gezondheidszorghulp tot kinderen helpen met problemen in gesproken en geschreven communicatie (Kambourie.a., 2023). Zoals Shakhovska e.a., 2019 ook aanduidt zullen nieuwe spraakherkenningstechnologieën en -methodes een centraal onderdeel
worden van het toekomstige leven omdat ze veel communicatietijd besparen en het gewone sms’en vervangen door spraak/audio.


Probleemstelling en onderzoeksdoelstellingen
Hoewel er aanzienlijke vooruitgang is geboekt in spraakherkenningstechnologie, blijven bepaalde problemen bestaan. De beschikbaarheid van commerciële spraakherkenningssystemen in het Nederlands is volgens het onderzoek van (Wei2022) beperkt.Dit leidt tot de vraag of huidige spraak-naar-tekst (STT) technologieën het Nederlands, inclusief regionale accenten en verschillen in taalgebruik, kunnen beheersen. Als gevolg hiervan zal het onderzoek de aanpassingsmogelijkheden en nauwkeurigheid van bestaande STT-systemen onderzoeken bij het vastleggen van verschillende linguïstische nuances in het Nederlands. Het doel is om inzicht te krijgen in de prestaties van STT-systemen in het Nederlands en potentiële verbeterpunten te vinden om de technologie in het Nederlands beter te gebruiken.

De primaire onderzoeksdoelstellingen omvatten:

- Het onderzoeken van de invloed van omgevingsgeluid op STT-nauwkeurigheid.
- Beoordelen van de geschiktheid van modellen getraind op verschillende talen voor STT-taken in het Nederlands.
- Het identificeren van open source en closed source modellen voor Nederlandse taalverwerking.
- Hoe presteert een geoptimaliseerd model op woorden die niet behoren tot de standaardtaal adhv. word error rate?
- Het evalueren van de haalbaarheid en efficiëntie van het implementeren van verbeterde STT-modellen in de praktijk.


Methodologie van het onderzoek
Om deze doelstellingen te bereiken, zal het onderzoek verschillende fasen doorlopen. Het zal beginnen met een uitgebreid literatuuronderzoek om het huidige landschap van STT-technologie in kaart te brengen en bestaande uitdagingen te identificeren. Vervolgens wordt in het hoofdstuk over methodologie de aanpak beschreven voor het onderzoeken en verbeteren van de transcriptiekwaliteit, met een specifieke focus op gesprekken met oudere mensen en studenten van HOGENT. In dit gedeelte worden het onderzoeksdesign, de methoden voor gegevensverzameling en de criteria voor de evaluatie van het model toegelicht.

Betekenis en verwachte resultaten
De resultaten van dit onderzoek zijn bedoeld om bij te dragen aan de vooruitgang van STT-technologie, in het bijzonder bij het verwerken van regionale accenten en (niet-standaard) Nederlands. De ontwikkeling van een geoptimaliseerd STT-model op maat voor Nederlands en taalvariaties wordt verwacht. Verder zullen de inzichten uit het onderzoek licht werpen op de uitdagingen en beperkingen in de huidige SR-systemen, waardoor de weg wordt vrijgemaakt voor toekomstig onderzoek en technologische verbeteringen in dit domein.

Samengevat is deze studie bedoeld om de mogelijkheden en beperkingen van STT-technologie te onderzoeken bij het aanpakken van taalkundige diversiteit, deze diversiteit wordt aangekaart in het onderzoek van (Ghyselen e.a., 2020) en (Barbiers &Bennis, 2004). Het uiteindelijke doel is het verbeteren van de nauwkeurigheid en bruikbaarheid van transcripties in verschillende taalkundige contexten.