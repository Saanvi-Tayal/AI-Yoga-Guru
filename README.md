# AI-Yoga-Guru

## Problem Statement
Many people are turning to at-home yoga for a healthier lifestyle. While this poses many benefits, not being able to work on their postures properly during practising yoga causes long-term injuries to go unnoticed.This model will first recognise the pose and then help remind the practitioner of what to pay attention to when practising that asana.

## Working Principle
In this model,the main factor ,to recognise the asana, is the angle between the joints. Using Mediapipe, landmarks of different body parts & joints will be detected and then arctan (function of numpy) will calculate the angles between those landmarks. According to the angles it will estimate the posture and then retrieve the instructions of that asana and then read out those instructions using the pyttsx3 library(text to speech)

## Domains Of AI
Computer Vision ,Natural Language Processing

## Dependencies
Mediapipe<Br>
pyttsx3

## Project Demo Video
https://youtu.be/Mb7nMfBYu_8
