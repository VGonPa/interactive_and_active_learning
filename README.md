# interactive_and_active_learning
Repo containing the Manuscript and the Slides of my PhD thesis

You can check the following media:

- [Manuscript](Manuscript-PhD_VGonzalez.pdf)
- Slides [PDF](Slides-PhD_VGonzalez.pdf) [Online](https://speakerdeck.com/vgonpa/interactive-and-active-learning-in-social-robots)
- [Video of the defense](https://youtu.be/VKuOaENl8k0)

Or check the code and the datasets that I developed during my PhD:

- [Pose Tracker](https://github.com/UC3MSocialRobots/pose_tracker_stack)
- [Ocular Project](https://github.com/UC3MSocialRobots/ocular_project)
- [Rospy Utils](https://github.com/UC3MSocialRobots/rospy_utils) (Some utilities to program ROS Nodes in a functional programming style)

- [Poses Dataset](https://github.com/VGonPa/datasets-poses2012)


# Abstract

The aim of this thesis is to study how social robots should interact with people when these people are teaching them new concepts. This objective is motivated by the need of having robots operating in real, unstructured environments where they have to cooperate or to socialize with humans. From a robot’s point of view, people have the –almost obsessive– tendency to be unpredictable. This unpredictability makes the job of programming the robot’s social behaviours a daunting task, especially if the robot’s programmer has to take into account all the possible situations that the robot may encounter during its life cycle. A common solution to this problem is to let the robot to learn continuously from its environment and from the people it interacts with. Our inspiration comes from the way children learn from their teachers, parents, or from other people. Generally, they ask for the concepts they do not understand (e.g. unknown objects, places, etc.) to adults. Our approach is to mix techniques from Supervised Machine Learning and Human Robot Interaction to enable a natural, interactive learning where the robot plays the role of a child asking to a human teacher. To achieve this, we study and apply techniques from Active Learning literature to enable the robot to decide which questions are more appropriate to ask and when its better to ask them. We apply these techniques in two different areas, human pose detection and object recognition, to enable the robot to detect the situations in which it needs to expand its knowledge so it can ask for it to its human partner.
