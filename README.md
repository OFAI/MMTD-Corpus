# OFAI Multi-Modal Task Description (MMTD) Corpus

The MMTD Corpus is a collection of 4 task-oriented datasets comprising audio (German), video and multimodal annotations. 
The respective datasets will be successively made available to the research community. For privacy reasons, however, only the annotations are public.

Details about how the data was collected can be found in [Stephanie Gross &  Brigitte Krenn: The OFAI Multimodal Task Description Corpus. LREC 2016]
(http://www.lrec-conf.org/proceedings/lrec2016/pdf/343_Paper.pdf). 

- [**Dataset 1 (released)**](http://www.ofai.at/research/interact/resources/mmtd/setup1_MMTD.tar.gz) is a collection of tasks where a human tutor arranges and rearranges fruit on a table, and explains what (s)he is doing to a camera for an anonymous learner to replicate the task. The dataset comprises scenes from 22 tutors. The data contain timestamps for each annotation and the begin time and the end time of the annotation are the first two entries in a row.

 The annotations are sorted by their tier and the following tiers are annotated in the following order:
 1. transliteration
 2. part-of-speech tags
 3. where the eye gaze of the instructor is directed at
 4. the type of gesture used by the instructor and what it depicts
 5. the relevant object (e.g. 'Banane' when 'Banane' or a pronoun referring to 'Banane' is uttered)
 6. touch hand: the object, the instructor is currently touching or holding
 7. touch ground: information about which objects are currently lying on the ground (table, plate, paper) or are off the ground. For instance: "+Erdbeere|Birne|Banane:ground=Teller" stands for 'the strawberry, pear and banana are lying on the plate'; "-Erdbeere:ground1=Teller:ground2=Blatt Papier" stands for 'the strawberry has left the plate and is put on the sheet of paper'; "-Erdbeere:ground=Teller" stands for 'the strawberry is taken from the plate and then is again put back on the plate'
 8. move object: the object which is currently moved and where to it is moved, for example: "Banane:onto=Blatt Papier" stands for 'the banana is moved onto the sheet of paper'; "Birne:nextto=Erdbeere" stands for 'the pear is moved next to the strawberry';
    
 - In **Dataset 2**, pairs of instructor and learner collaboratively move a single object. The dataset comprises data from 22 human-human pairs.
 
 - [**Dataset 3 (HHI released)**](http://www.ofai.at/research/interact/resources/mmtd/setup3_MMTD.tar.gz) is a collection of multimodal scenes where a tutor explains to a copresent human (HHI) or robot (HRI) how to mount a tube in a box with holdings. The dataset comprises data from 16 human-human pairs and 6 human-robot pairs. The data contain timestamps for each annotation and the begin time and the end time of the annotation are the first two entries in a row.
  
  The annotations are sorted by their tier and the following tiers are annotated in the following order:
  1.  transliteration
  2. part-of-speech tags
  3. where the eye gaze of the instructor is directed at
  4.  the type of gesture used by the instructor and what it depicts
  5. the relevant object (e.g. 'green and yellow marker' when 'the thing' is uttered)
  6. the object, the instructor is currently holding or still holding (still holding refers to objects, which the instructor has still in his/her hands although he/she has grasped another object in the meantime),
  7. information about the object / target where another object currently moves
  8. metadescriptions, e.g. summarizations at the beginning of the task or statements with regards to their own performance
    
  - [**Dataset 4 (HHI released)**](http://www.ofai.at/research/interact/resources/mmtd/setup4_MMTD.tar.gz) represents a navigation task where a human tutor explains to a human (HHI) or robot (HRI) how to move from location A to location B. The dataset comprises scenes from 16 human-human pairs and 6 human-robot pairs. The data contain timestamps for each annotation and the begin time and the end time of the annotation are the first two entries in a row.
    
   The annotations are sorted by their tier and the following tiers are annotated in the following order:
   1. transliteration
   2. part-of-speech tags
   3. where the eye gaze of the instructor is directed at
   4. the type of gesture used by the instructor and what it depicts
