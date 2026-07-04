
<div align="center">
<img src="images/image.png"  width="10%">
</div>

# Intro to Amazon SQS

"Message Queuing Service"

## Use-Case: Restoring Image Application

Medium Corp is designing an application that will enhance and restore the images that
users submit through the online portal.

<div align="center">
<img src="images/image1.png"  width="65%">
</div>

# Current Architecture

The overall architecture involves two components:

1. Image Gatherer - Takes the Images from the user via Upload button.
2. Imager Enhancer - Receives the Image from Image Gatherer.

<div align="center">
<img src="images/image2.png"  width="65%">
</div>

## Challenges

Due to popularity of the application and huge traffic spike, Medium Corp has decided to
add more image enhancer servers.

<div align="center">
<img src="images/image3.png"  width="65%">
</div>

## Better Architecture

One of the main function of message queue service is to take message from a Publisher
and forward that to a consumer.

The queue stores these messages internally.

<div align="center">
<img src="images/image4.png"  width="65%">
</div>

## Introduction to SQS

Amazon SQS is a fast reliable, scalable, and fully managed message queuing service.

Amazon SQS makes it simple and quiet cost effective to decouple the components of a
specific application.

<div align="center">
<img src="images/image5.png"  width="65%">
</div>

## Tightly Coupled Systems

Components of system architecture directly communicate with each other and have
hard-dependency on each other.

<div align="center">
<img src="images/image6.png"  width="65%">
</div>
## Loosely Coupled System

Components of system architecture that can process the information without being
directly connected.

<div align="center">
<img src="images/image7.png"  width="65%">
</div>
