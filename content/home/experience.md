+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = "Internships"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "Research Intern"
  company = "Prof. Katerina Fragkiadaki"
  company_url = ""
  location = "Machine Learning Department, Carnegie Mellon University"
  date_start = "2019-05-10"
  date_end = "2019-07-29"
  description = """
Visited as SN Bose Scholar:

* Worked on learning trainable 3D visual representation for robot control.
* The whole code was written on Nvidia FleX, a simulator which runs completely on the GPU, hence decreasing sampling time of the
replay buffers while training RL agents.

  """

[[experience]]
  title = "Winter Research Intern"
  company = "Prof. R. Venkatesh Babu"
  company_url = ""
  location = "Video Analytics Lab, Indian Institute of Science"
  date_start = "2018-12-01"
  date_end = "2019-01-31"
  description = """
Visited the Video Analytics Lab during the winters:

* Developed a top-down multi-generator model which use a hierarchical divisive strategy to address discontinuous multi-modal data.
* Developed novel mode splitting algorithm to effectively split the parent node to semantically cohesive children nodes, facilitating unsupervised clustering.
* Built multi-generator model such that incremental addition of new data modes to an already trained GAN-Tree is possible, by updating only a single branch of the tree structure.
* First top-down approach in the field of multi-generator models which does not require prior definition of the number of generators."""

[[experience]]
  title = "Remote Research Intern"
  company = "Prof. Marco Pedersoli, Prof. Jose Dolz"
  company_url = ""
  location = "École de Technologie Superieure (ETS), Montreal"
  date_start = "2018-05-01"
  date_end = "2018-07-31"
  description = """
Worked remotely as a summer intern:

* Developed an end-to-end model to learn scenic and facial features jointly using attention mechanisms for identifying the emotion
portrayed by an image of a group of people.
* The model was submitted to ICMI 2018 EmotiW Group-Level Emotion Recognition Challenge and achieved 4th rank among all participants. A short paper for the same was also accepted in the challenge.

"""

+++
