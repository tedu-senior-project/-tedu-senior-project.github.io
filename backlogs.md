---
layout: index
title: Backlogs
---

<ul class="nav nav-tabs" id="myTab" role="tablist">
  <li class="nav-item" role="presentation">
    <a class="nav-link active" id="home-tab" data-toggle="tab" href="#home" role="tab" aria-controls="home" aria-selected="true">Home</a>
  </li>
  <li class="nav-item" role="presentation">
    <a class="nav-link" id="profile-tab" data-toggle="tab" href="#profile" role="tab" aria-controls="profile" aria-selected="false">CMPE 491</a>
  </li>
  
</ul>
<div class="tab-content" id="myTabContent">
  <div class="tab-pane fade show active" id="home" role="tabpanel" aria-labelledby="home-tab">...</div>
  <div class="tab-pane fade" id="profile" role="tabpanel" aria-labelledby="profile-tab">
  
  <br>

  {% include 491backlog.html %}


<br>

  </div>
</div>

{{< bootstrap-table "table table-dark table-striped table-bordered" >}}
| Task Name                                    | Category       | Priority | Status      |
| -------------------------------------------- | -------------- | -------- | ----------- |
| **Sprint1**                                  |
| **Dataset**                                  |
| Searching appropriate datasets               | Research       | High     | In progress |
| Contacting datasets owner                    | Research       | High     | In progress |
| Investigating found datasets                 | Research       | Low      | Not started |
| **Reports**                                  |
| Low-Level Design Report                      | Report         | High     | Completed   |
| Low-Level Design Report Updated              | Report         | Medium   | In progress |
| Test-Plan Report                             | Report         | Low      | Not started |
| Final Report                                 | Report         | Low      | Not started |
| **Literature Reviewing**                     |
| Finding relative papers according to subject | Research       | Medium   | In progress |
| Reading found papers                         | Research       | Medium   | In progress |
| Searching promising techniques               | Research       | Medium   | In progress |
| **GUI**                                      |
| Research on GUI Builders                     | Research       | Medium   | In progress |
| Designing GUI                                | Implementation | Medium   | In progress |
| Implementing GUI                             | Implementation | Medium   | In progress |
| **Implementation**                           |
| Finding appropriate classifiers              | Research       | High     | Completed   |
| Implementing classifiers                     | Implementation | High     | Completed   |
| Detection & Tracking of Face and Eye         | Implementation | High     | Completed   |
| Detection of Mouth                           | Implementation | Medium   | Not started |
| Counting Eye Blink                           | Implementation | High     | Completed   |
| Integration System with RaspberryPi          | Implementation | Medium   | Not started |
| **Training Model**                           |
| Research on Haar, LBP                        | Research       | High     | In progress |
| Research on OpenCV                           | Research       | High     | In progress |
| Research on SVM                              | Research       | High     | In progress |
| Research on Anomaly Detection                | Research       | High     | In progress |
| **Demo**                                     |
| Preparing Demo                               | Decision       | Low      | Not Started |
{{< /bootstrap-table >}}