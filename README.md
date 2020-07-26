<h2><span style="color: #ff6600;">Introduction</span></h2>
<p><a href="http://www.siminbook.com/" target="_blank" rel="noopener"><span style="color: #0000ff;"><strong>SiminBooks</strong></span></a> is a charity organization, which believes in <span style="color: #3366ff;">public lecture</span> (also know as <span style="color: #3366ff;">open lecture</span>). in order to accomplish this goal, <span style="color: #0000ff;">SiminBooks</span> is raising money in order to buy and deliver books for people who are very poor.</p>
<p><span style="color: #0000ff;">SiminBooks</span> development team has decided to use <span style="color: #3366ff;">blockchain trusted transaction networks</span> in order to make <span style="color: #ff0000;">donators</span> assure that, their money will be put on good use. due to this, <span style="color: #0000ff;">SiminBooks</span>'s development team has decided to implement Hyperledger Fabric network on a Ubuntu(18.04) server.</p>
<p>In order to run the network, we have installed some prerequisites, which they are listed below:</p>
<ul>
<li>cURL</li>
<li>Docker and Docker Compose</li>
<li>Javascript</li>
<li>Go</li>
<li>Node.JS</li>
</ul>
<p>once we were ready, we installed the Fabric Samples and binaries using the command below to pull down the binaries and images.</p>
<table style="border-color: blue; margin-left: auto; margin-right: auto;" border="1">
<tbody>
<tr>
<td>curl -sSL https://bit.ly/2ysbOFE | bash -s</td>
</tr>
</tbody>
</table>
<p>as we made it through we brought up our first network using the command below</p>
<table style="border-color: blue; margin-left: auto; margin-right: auto;" border="1" cellpadding="2">
<tbody>
<tr>
<td>
<p>./network.sh up</p>
</td>
</tr>
</tbody>
</table>
<p>Hyperledger Fabric offers a number of SDKs to support developing applications in different types of programming languages which will be listed below:</p>
<ul>
<li>Go contract-api</li>
<li>Node.js contract API and Node.js contract API documentation</li>
<li>Java contract API and Java contract API documentation</li>
</ul>
<p>For more information please visit <a href="https://hyperledger-fabric.readthedocs.io/" target="_blank" rel="noopener">Hyperledger Fabric's website</a>.</p>
