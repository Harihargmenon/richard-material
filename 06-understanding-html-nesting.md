---
title: "Basics Of HTML Nesting"
---

# Understanding Nesting in HTML

Nesting is a way of placing one HTML element inside another. This can be used to create more complex and sophisticated layouts for your web pages. Let’s imagine we are a list of your favourite cricket batsmen, and now for each batsman let's list their top 3 scores. You see in this setup, each batsman score list is nested inside the overall list. We will find such relationships between different tags as we learn HTML in more depth. Here the outer tag is the parent tag to the children inside it.
Eg List of Cricketers and their top 3 scores
```html
<ul>
  <li>Virat Kohli
    <ol>
      <li>165</li>
      <li>145</li>
      <li>135</li>
    </ol>
  </li>
  <li>Rohit Sharma
    <ol>
      <li>185</li>
      <li>155</li>
      <li>125</li>
    </ol>
  </li>
  <li>Babar Azam
    <ol>
      <li>205</li>
      <li>145</li>
      <li>115</li>
    </ol>
  </li>
</ul>
```
This list looks something like :
<ul>
  <li>Virat Kohli
    <ol>
      <li>165</li>
      <li>145</li>
      <li>135</li>
    </ol>
  </li>
  <li>Rohit Sharma
    <ol>
      <li>185</li>
      <li>155</li>
      <li>125</li>
    </ol>
  </li>
  <li>Babar Azam
    <ol>
      <li>205</li>
      <li>145</li>
      <li>115</li>
    </ol>
  </li>
</ul>
In this case inner list becomes the child to the parent outer list.
