# DeepVISS-OPS


# TODOs
Tactical:
* add Attributes


## Strategic:
Feature Map
Landmark Map
Profile -> Attributes
Latency Vector
Exception Handling


## Unstructured:



###1
Stream specific tracking ID (SSTI)


Add privacy descriptors on signatures and items
Hide null or absent fields (from serializer)




Add collection, profile, face, temporary face (expiry)


Modelling object permanence in computer vision / using a hash/id to track objects across frames
.


Descriptors to add on all objects:
* description
* ....


Streamuri finite (legate la fisier)
Stream event changes
Streamuri stateless
Streamuri de pozitie fixa


Extensii de obiecte
Exercitiu mapare securifai, crowdlens
Exercitiu mapare posenet


How can we use anyOf type?
How does it map to cast and arrays?




How can we use binary or byte(base64) in DeepVISS?


Binar ca si continut al frame-ului
Serialuzare in layer date (elasticsearch) a entitatilor de transport
Cautare lsh/random projection in elasticsearch


EyeTracking
Direction Vectors
3D Direction Vectors
3D Rotation Vectors

DONE Specificare Request


DONE Loc in response pentru modificarea imaginii

## 2
To add to DeepVISS OPS:
• residue / generational residue / vector-archived / encoded as mpeg :rolling_on_the_floor_laughing:/ generational-differential
• action, typed-timebound-relationship between items ; messages are conceptualized as actions;this is a separate collection from that of Events; it is a collection of ( action(initator, receiver, attributes) )
• STEM coverage, including telemetry, stereoscopy and odometet

• trackingId and co-occurence logic ;
• spatial-perceptual graph (of objects) - this is a separate collection from that of Events; shows compacted neighborhood-representational, but in perception and in vecinity
• how do you deal with representational polymorphism (solution: map each objectType to a entry in a semantic, graph-based, multi-representational);
• support for judging robustness, confidence, whatif confidence (feature extract over filters)
• whatif and long-running what-if query for multi-functor analysis on items
• conversations as MediaItems
• dictionaries of semantic record for various object types (links back to data set and to trained models)
• semantic ocr tagging
• text tagging (based on patches, like a double-linked list); articles as MediaItems
• code as a MediaItem
• tests/validations/quantized validations

•Define morphism between TAG and OPS
Make sure DEEPVISS OPS is proxyable and proxy-orthogonal

• in DEEPVISS TAG define “Ellicitor”: the question or game, based on existent data, possibly pre-clustered, pre-filtered, pre-tagged, in a quantized minimum-user-interruption/effort for speeding up the minimization of uncertainty and representational residue , with one or several player-avatars, not necesarilly all human-backed, not necessarily all machine-backed


