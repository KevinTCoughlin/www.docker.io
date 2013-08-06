{% extends 'community.html' %}{% load staticfiles %}
{% block title %}Community - {% endblock %}
{% block meta-description %}Join the thousands of developers who are helping to lead the Docker revolution!{% endblock %}
{% block meta-keywords %}Docker, community, cobntribute{% endblock %}


{% block copy_headline %}
get involved with the docker community by contributing and sharing
==================================================================
{% endblock %}

{% block copy_introduction %}

## About the community

Join the thousands of developers who are helping to lead the Docker revolution! Joining our community is a great way to
interact with other talented developers and devops professionals, increase awareness of the work that you are doing,
improve your skills, or give back.

{% endblock %}

{% block copy_1 %}

### Get in Touch ##

There are several ways to get in touch:

<ul id="chooser-blocks" class="option-chooser-blocks">

    <a id="block-irc" data-description="A lot of our talk goes on on our IRC channel. You can find us as #docker on irc.freenode.net"
       href="https://botbot.me/freenode/docker/#"
       target="_blank"><li>IRC (via BotBot)<img src="{% static 'img/community/IRC.png' %}"> </li></a>

    <a data-description="Getting in touch and discussing features can best be done on the google group."
       href="https://groups.google.com/forum/#!forum/docker-club"
       target="_blank"><li>Google groups<img src="{% static 'img/community/google-groups.png' %}"> </li></a>

    <a data-description="All development goes on in Github. It is a your destination to contribute, find and commit problems"
        href="http://github.com/dotcloud/docker"
        target="_blank"><li>Github<img src="{% static 'img/community/github.png' %}"> </li></a>

    <a data-description="Ask questions about how to use Docker on Stack Overflow, so anyone can benefit from the answers"
        href="http://stackoverflow.com/search?q=docker"
        target="_blank"><li>Stackoverflow<img src="{% static 'img/community/stackoverflow.png' %}"> </li></a>

    <a data-description="For general praise, and other chitter chatter tweet"
        href="http://twitter.com/docker/"
        target="_blank"><li>Twitter<img src="{% static 'img/community/twitter.png' %}"> </li></a>
</ul>

<strong><span id="description" class="">So many options!</span></strong>

{#<iframe id="bbme" src="http://botbot.me/freenode/docker/" width="615" height="400"></iframe>#}
{#<iframe src="https://kiwiirc.com/client/irc.freenode.net/#docker" style="border:0; width:100%; height:450px;"></iframe>#}

{#<div class="botbot-button">#}
{#    <img src="{% static 'img/community/botbot-white.svg' %}">#}
{#    <span class="bbme-title">irc logs</span>#}
{#</div>#}

## Share

Sharing what you have built with Docker is a great way to help people understand the value of Docker. If you have
    a great story to tell we'll be happy to help you spread the word.

* Tell your story at a company tech talk, tweet (#docker.io, @docker)  present at your local user group, or submit a
    talk proposal to a conference or event about how you are using Docker
* If you are using Docker,  in production, become a public reference like [these](http://blog.docker.io/2013/07/docker-projects-from-the-docker-community/)
* Write a tutorial like [these](http://blog.docker.io/2013/06/14-great-tutorials-on-docker/)



### Come to (or organize) a meetup ###

<img src="{% static 'img/community/hackday_demo.jpg' %}" alt="Demo at Docker Hackday" class="float-right" style="width: 250px;">

Docker meetups  are a great way to network, learn, share best practices, and have fun.

* Find or organize a [meetup](http://www.meetup.com/Docker-meetups/)

### Share or Create New Dockerized Apps ###
There are over 1,000 cool, containerized applications in our public Index.

* Search for containers in the [Index](https://index.docker.io/)
* Publish containers at the Index
* Better yet, create a Dockerfile and put it in your repository, to make creation of new containers automatic


## Contribute

An Open Source project like Docker couldn’t exist without contributions from the developer community.
    As of June 30, 2013, there are over 100 contributors and nearly 400 forks on the project.

* Take a look at our [issues list](https://github.com/dotcloud/docker/issues?state=open) and consider submitting a patch
* Review our roadmap on [GitHub](https://github.com/dotcloud/docker) and provide feedback
* Consider [contributing](https://github.com/dotcloud/docker/blob/master/CONTRIBUTING.md).

Like the program itself, we run the [**documentation**](http://docs.docker.io) as an open source project. The sources are
    available from the main [docker repository](https://github.com/dotcloud/docker/tree/master/docs) on Github, and we
    encourage you to make improvements, whether big or small, make a pull request.

### Work on Docker ###
Like to hack on Docker? Work on it full time! Come look at our [jobs](http://dotcloud.theresumator.com/apply/) listing.

{% endblock %}


{% block copy_2 %}

## What people have already built using Docker

Docker is a powerful tool for many different use cases. Here are some great early use cases for Docker, as described by members of our community.

<table class="docker_use_cases_table table">
	<thead>
		<tr>
			<td>
				Use Case
			</td>
			<td>
				Examples
			</td>
			<td>
				Link
			</td>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>
				Build your own PaaS
			</td>
			<td>
				Dokku - Docker powered mini-Heroku. The smallest PaaS implementation you’ve ever seen
			</td>
			<td>
				<a href="http://bit.ly/191Tgsx">http://bit.ly/191Tgsx</a>
			</td>
		</tr>
		<tr>
			<td>
				Web Based Environment for Instruction
			</td>
			<td>
				JiffyLab – web based environment for the instruction, or lightweight use of, Python and UNIX shell
			</td>
			<td>
				<a href="http://bit.ly/12oaj2K">http://bit.ly/12oaj2K</a>
			</td>
		</tr>
		<tr>
			<td rowspan=3>
				Easy Application Deployment
			</td>
			<td>
				Deploy Java Apps With Docker = Awesome
			</td>
			<td >
				<a href="http://bit.ly/11BCvvu">http://bit.ly/11BCvvu</a>
			</td>
		</tr>
		<tr>
			<td>
				Running Drupal on Docker
			</td>
			<td>
				<a href="http://bit.ly/15MJS6B">http://bit.ly/15MJS6B</a>
			</td>
		</tr>
		<tr>
			<td>
				Installing Redis on Docker
			</td>
			<td>
				<a href="http://bit.ly/16EWOKh">http://bit.ly/16EWOKh</a>
			</td>
		</tr>
		<tr>
			<td>
				Create Secure Sandboxes
			</td>
			<td>
				Docker makes creating secure sandboxes easier than ever
			</td>
			<td class="td3">
				<a href="http://bit.ly/13mZGJH">http://bit.ly/13mZGJH</a>
			</td>
		</tr>
		<tr>
			<td>
				Create your own SaaS
			</td>
			<td>
				Memcached as a Service
			</td>
			<td>
				<a href="http://bit.ly/11nL8vh">http://bit.ly/11nL8vh</a>
			</td>
		</tr>
		<tr>
			<td>
				Automated Application Deployment
			</td>
			<td>
				Push-button Deployment with Docker
			</td>
			<td>
				<a href="http://bit.ly/1bTKZTo">http://bit.ly/1bTKZTo</a>
			</td>
		</tr>
		<tr>
			<td>
				Continuous Integration and Deployment
			</td>
			<td>
				Next Generation Continuous Integration &amp; Deployment with dotCloud’s Docker and Strider
			</td>
			<td>
				<a href="http://bit.ly/ZwTfoy">http://bit.ly/ZwTfoy</a>
			</td>
		</tr>
		<tr>
			<td>
				Lightweight Desktop Virtualization
			</td>
			<td>
				Docker Desktop: Your Desktop Over SSH Running Inside Of A Docker Container
			</td>
			<td>
				<a href="http://bit.ly/14RYL6x">http://bit.ly/14RYL6x</a>
			</td>
		</tr>
	</tbody>
</table>

{% endblock  %}


