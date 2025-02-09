# React Native FlatList Crash with Large Datasets

This repository demonstrates a common performance issue in React Native's FlatList component when handling very large datasets.  The bug exhibits as unresponsiveness and eventually a crash, often manifested as a blank screen or application freeze.  The included code showcases the problem and a potential solution.

## Problem

FlatList, while efficient for smaller lists, can struggle with large datasets.  Inefficient rendering and memory management can lead to performance degradation and application crashes.

## Solution

The solution involves implementing pagination, virtualization, or a combination of techniques to efficiently render only the visible items in the list, reducing memory consumption and improving performance. The example solution includes using `windowSize` to manage pagination effectively.