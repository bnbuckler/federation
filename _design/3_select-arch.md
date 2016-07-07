---
layout: page_collection
title: Select the Optimal Architecture Solution
collection: design
permalink: design/3_select-arch/
---
<script>
$(function() {
  $( "#accordion" ).accordion({
    heightStyle: "content",
    collapsible: "true",
    active: "false"
  });
});
</script>
---------------------------------------------------------------------

In order for an agency to select a solution architecture, it is important to understand which architecture is most applicable to its situation. It is recommended that an agency use the information collected from the assessments during the agency's planning period to determine its optimal solution architecture. 

The chart below provides guidance to the applicability of each architectural solution. Within the chart, the enterprise and federation broker architecture solutions share certain situations where either one may be appropriate. These approaches both support streamlined integration of multiple applications but differ in the amount of control the agency keeps in implementing and managing the federation solution. An agency should consider each of its requirements to determine the best architectural approach.

<br>

| <center> Recommended Approach </center> | <center> Situations </center> |
|:----------------------------------------:|------------------------------|
| **Stand-Alone** | • An agency has a small number of applications that require the acceptance of third-party credentials. <br><br> • An agency wishes to pilot the acceptance of third-party credentials on a small scale before deploying it for the entire agency. |
| **Enterprise** | • An agency wishes to maintain control of which Credential Service Providers (CSPs) are integrated and the connection to those CSPs. <br><br> • An agency has many applications that are required to accept third-party credentials. <br><br>• An agency has existing agency-wide infrastructure that can be modified/augmented to accept third-party credentials. |
| **Federation Broker** | •	An agency has many applications that are required to accept third-party credentials. <br><br> • An agency has existing agency-wide infrastructure that can be modified/augmented to accept third-party credentials. <br><br> •	An agency wishes to accept third-party credentials from a large user base that spans many CSPs. <br><br> • An agency with privacy requirements to accept externally-issued credentials without knowing to which CSP a user authenticated. |



