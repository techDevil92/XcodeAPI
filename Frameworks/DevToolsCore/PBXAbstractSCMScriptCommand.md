---
layout: default
title: PBXAbstractSCMScriptCommand
breadcrumbs: <a href="/index.html">Main</a> &raquo; <a href="/Frameworks.html">Framework</a> &raquo; <a href="/Frameworks/DevToolsCore.html">DevToolsCore</a> &raquo; PBXAbstractSCMScriptCommand
parent: NSObject 
---

# PBXAbstractSCMScriptCommand Class Reference

*Framework* /Developer/Library/PrivateFrameworks/DevToolsCore.framework

## Overview

The PBXAbstractSCMScriptCommand class provides an interface for running source control commands via a script.

## Tasks

### Creating a PBXAbstractSCMScriptCommand Object

[- initWithCommandDescription:](#-initWithCommandDescription:)

### Obtaining Return Values Object

[- returnValueFromInfo:](#-returnValueFromInfo:)

[- returnScriptResultUsingInfo:](#-returnScriptResultUsingInfo:)

### Requests

[- requestDidFinish:](#-requestDidFinish:)

[- performRequestWithItems:onSCMManager:](#-performRequestWithItems:onSCMManager:)

[- runCommandOnItems:inProject:](#-runCommandOnItems:inProject:)

[- runCommandOnProject:](#-runCommandOnProject:)

[- argumentsForRequest](#-argumentsForRequest)

[- requestType](#-requestType)

## Instance Methods

<a name="-initWithCommandDescription:"></a>
###initWithCommandDescription:
    - (id)initWithCommandDescription:(id)arg1

### returnValueFromInfo:
    - (id)returnValueFromInfo:(id)arg1

### returnScriptResultUsingInfo:
    - (void)returnScriptResultUsingInfo:(id)arg1

### requestDidFinish:
    - (void)requestDidFinish:(id)arg1

### performRequestWithItems:onSCMManager
    - (id)performRequestWithItems:(id)arg1 onSCMManager:(id)arg2

### runCommandOnItems:inProject:
    - (id)runCommandOnItems:(id)arg1 inProject:(id)arg2

### runCommandOnProject
    - (id)runCommandOnProject:(id)arg1

### argumentsForRequest
    - (id)argumentsForRequest

### requestType
    - (id)requestType


