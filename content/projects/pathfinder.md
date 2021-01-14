+++ 
draft = true
date = 2020-12-30T17:34:42+01:00
title = "Pathfinder"
description = "Python GUI application to visualize Dijkstra and A* SPF algorithms. It uses pygame and also features a maze generator."
authors = []
tags = ["shortest path first", "all shortest paths", "maze", "pygame"]
Lang = "Python"
externalLink = ""
math = "true"
+++

## Dijkstra

{{< figure src="https://upload.wikimedia.org/wikipedia/commons/e/e4/DijkstraDemo.gif" caption="Dijkstra's Algorithm visualized" width="300">}}

Dijkstra's Algorithm can be seen as a form of depth first algorithms meaning that it explores all of the neighbor nodes at the present 'level' prior to moving on to the neighbors of neighbors and so on. The way Dijkstra's Algorithm extends that behaviour is in the way the next neighbor to explore is chosen. Let's introduce some formalities to further explore how the algorithm works.

Let $G = (V, E)$ be a graph where 
$$
V = \lbrace node \mid \text{ node in G } \rbrace, E = \lbrace (u, v) \mid u,v \in V \land \text{ u,v neighbors } \rbrace
$$
and $c: E \to \mathbb{N}_+$ be a function which determines the costs of a edge between two nodes.

{{< highlight c "linenos=table" >}}

{{< / highlight >}}

## A*