<h2>maxent_toolbox</h2>

<p>Maximum entropy toolbox for MATLAB is a toolbox for fitting discrete maximum entropy distributions to experimental data. 
Maximum entropy models are a method to approximate probability distributions of discrete states from a limited amount of 
samples, where standard approaches (such as counting the states) cannot be applied.</p>
<p>This toolbox is intended for learning probability distributions of <b>binary activity patterns</b>, i.e. patterns in the form
1000110100. Examples of problems where one might want to learn such distributions are characterising the joint
activity of neural populations (0/1 denoting if a certain neuron fired with a small time window) or gene expression profiles
(0/1 denoting if a certain gene is being expressed).</p>
<p>The basic function of the toolbox is using a limited set of example activity patterns 
to extrapolate the entire distribution over all possible activity patterns. To do this the user can choose between
several different "flavors" of maximum entropy models, each of which makes different types of assumptions over the input. 
The types of maximum entropy models currently supported by this package are:
<ul>
<li>Independent model</li>
<li><a href="http://www.weizmann.ac.il/neurobiology/labs/schneidman/Publications/Schneidman+al_2006-Nature.pdf">Pairwise maximum entropy model</a></li>
<li><a href="http://wp.ist.ac.at/group_tkacik/wp-content/uploads/2011/02/JStatMech_Simplest_Maxent.pdf">K-synchrony model</a></li>
<li><a href="http://wp.ist.ac.at/group_tkacik/wp-content/uploads/2011/02/PLOSCompBio_KPairwise.pdf">K-Pairwise model</a></li>
<li>Arbitrary set of high-order correlations</li>
<li><strike>MERP model</strike> (coming soon)</li>
<li>Any combination of the above models</li>
</ul>
</p>

<p>The toolbox uses MCMC methods and can be used to learn distributions of up to hundreds of 
binary variables. While the interface of the toolbox is in MATLAB, most of the code is written in heavily optimized C++ 
and is precompiled for Windows (64 bit), OS X and and Linux (CentOS).</p>

<h2>Download</h2>

<ul>
<li><a href="https://github.com/orimaoz/maxent_toolbox/releases/latest">Download latest version</a> packaged as an installable MATLAB toolbox with mex files precompiled for Windows 64bit, MacOS and Linux (CentOS 64bit).</li>
<li><a href="https://github.com/orimaoz/maxent_toolbox">Download most recent source code</a>.</li>
</ul>
        
<h2><a id="documentation" class="anchor" href="#documentation-list" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Documentation</h2>
<p>If this is the first time you are using the toolbox, start by reading the <a href="quickstart.html">quick start guide</a>.</p>
<p>Existing users may want to refer to the <a href="function_reference.html">function reference</a> for details about each of the available functions in the toolbox.</p>
<p>Answers to some frequently asked questions are available <a href="faq.html">here</a>.</p>


<h2><a id="build" class="anchor" href="#build" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Build</h2>
<p>Build instructions for Windows, MacOS and Unix are available <a href="build.html">here</a>.

<h2>License</h2>
<p>The Maximum Entropy Toolbox for MATLAB is free and open source, distributed under the <a href="https://en.wikipedia.org/wiki/MIT_License">MIT license</a>.</p>

<h2>
<a id="authors-and-contributors" class="anchor" href="#authors-and-contributors" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Authors and Contributors</h3>
<p>Ori Maoz, <a href="mailto:orimaoz@gmail.com"> orimaoz@gmail.com</a></p>