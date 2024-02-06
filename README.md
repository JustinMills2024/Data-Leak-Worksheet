<h1>Data Leak Worksheet</h1>


<h2>Incident Summary: </h2>
<br>A sales manager shared access to a folder of internal-only documents with their team during a meeting. The folder contained files associated with a new product that has not been publicly announced. It also included customer analytics and promotional materials. 



After the meeting, the manager did not revoke access to the internal folder but warned the team to wait for approval before sharing the promotional materials with others.

During a video call with a business partner, a member of the sales team forgot the warning from their manager. The sales representative intended to share a link to the promotional materials so that the business partner could circulate the materials to their customers. 

However, the sales representative accidentally shared a link to the internal folder instead. Later, the business partner posted the link on their company's social media page assuming that it was the promotional materials.


<br />


<h2>Report</h2>
<table border="1">
  <tr>
    <th>Control</th>
    <th>Least privilege</th>
  </tr>
  <tr>
    <td>Issue(s)</td>
    <td>What factors contributed to the information leak?<br>
      The factors are manager shared access to a folder with the team during a meeting. The new product has not been publicly announced yet and the manager did not revoke access. The sales rep accidentally shared the link and posted the link on the company social media page, publicly sharing the confidential folder of the new product.</td>
  </tr>
  <tr>
    <td>Review</td>
    <td>What does NIST SP 800-53: AC-6 address?<br>
      The NIST SP 800-53 addresses how an organization can protect their data by privacy by implementing least privilege.</td>
  </tr>
  <tr>
    <td>Recommendation(s)</td>
    <td>How might the principle of least privilege be improved at the company?<br>
      - Restrict access to sensitive resources based on user role.<br>
      - Automatically revoke access to information after a period of time.<br>
      - Regularly audit user privileges.</td>
  </tr>
  <tr>
    <td>Justification</td>
    <td>How might these improvements address the issues?<br>
      This would have prevented the information from being shared. Data leaks can be prevented if shared links to internal files are restricted to employees only. Limiting access and limiting sensitive information among employees would prevent this from happening and auditing accounts of who has access to the folder.</td>
  </tr>
</table>




