# BPMN and Petri Net for a Painting School


The scenario is that of a painting school that has to handle student requests.</br>

## Notes on the Business Process

The student first contacts the school and receives a list of available courses. The student chooses a course and the school connects him to a teacher. The teacher proposes a date and place for the first lesson, and the student can either accept, or propose different date and place until the date is set. Before each class, the learner receives a list of techniques and tools on which to acquire basic knowledge before employing them during the lesson. </br>

During the meeting the student prepares a series of sketches and drafts: the tutor describes each step of the process, the student follows the instructions and in case of doubt he asks the teacher for advice. At the end of each meeting, a selected one of the drafts that the student must complete at home, digitize and send to the teacher. The selection of the draft to be completed is made at the teacher's suggestion, until the student accepts. After having payed digitally, the pupil and the teacher can agree on a new meeting (with the process described above), or the student may decide to end the course. </br>

If the course is terminated, the client just informs the school and the process ends. </br>

The school is considering opening new courses, there is a need to consider also this occurence where the learner can choose whether to start a new learning path after terminating a course (to simplify the analysis we need to consider a student that follows a single course at a time).

## BPMN Diagram
<img src="https://raw.githubusercontent.com/lwdovico/BPM-project/main/BPMN/original.png" alt="BPMN Original" width="700">
<img src="https://raw.githubusercontent.com/lwdovico/BPM-project/main/BPMN/variant.png" alt="BPMN Variant" width="700">

## Petri Nets
<img src="https://raw.githubusercontent.com/lwdovico/BPM-project/main/PetriNets/full_petri_net_original.png" alt="BPMN Original" width="700">
<img src="https://raw.githubusercontent.com/lwdovico/BPM-project/main/PetriNets/full_petri_net_variant.png" alt="BPMN Variant" width="700">

## Tools Used

We used BPMN.io to produce the bpmn diagram. To analyze the Petri Nets we used WoPeD and Woflan. </br>

<a href="https://github.com/bpmn-io/bpmn-js"><img src="https://tinypic.host/images/2023/02/22/6481734.png" alt="BPMN.io" width="70"></a>
<a href="https://github.com/woped/WoPeD"><img src="https://tinypic.host/images/2023/02/22/4WoYdauf_2x.jpg" alt="Woped" width="70"></a>
<a href="https://www.win.tue.nl/woflan/"><img src="https://tinypic.host/images/2023/02/22/r4cHVBPz_2x.jpg" alt="Woflan" width="70"></a>