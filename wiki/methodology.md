# Methodology

## Summary

A lot of things were lost on my when I started this journey. As I learned not only how to do things but the why, I decided to share that knowledge wherever possible. This repo is designed with my opinionated setup of esphome and here I explain my reasoning and my decisions. I am open to suggestions and time permitting, I can answer any questions you might have.

## mqtt

I use MQTT in my home because it helps me understand work better. It also allows for automations to be carried out outside of home assistant. I have a hodge podge of devices I have picked up including zigbee, esphome, hasp, and a few shellies I have still functioning all connect to my mqtt server. 

## Security

Only thing missing to do what I did is a secrets.yaml which is by design. There are a lot of articles discussing this if you haven't heard of it doing it this way before. I did include a sample [secrets.yaml.example](../secrets.yaml.example) so you can understand how it works. I use git to save my changes, so secrets.yaml is in the .gitignore and a copy is kept in my key vault. 

## poetry

I use poetry for fast environment setup. If you have it installed, you can run ```poetry install``` and it will buld the environment with the exact versions I used.

