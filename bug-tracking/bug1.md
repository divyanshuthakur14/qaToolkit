# BUG1: Video player freezes when switching quality rapidly

**Date:** 2025-05-27  
**Reporter:** QA Team  
**Environment:** Chrome 112, Windows 11  

## Description  
When a user quickly switches video quality settings multiple times in a short span, the video player freezes and stops responding until the page is refreshed.

## Steps to Reproduce  
1. Open any video on https://youtube.com  
2. Click the settings icon and change video quality quickly several times (e.g., 1080p to 720p to 480p)  
3. Observe if the player freezes  

## Expected Result  
Video quality changes smoothly without freezing.

## Actual Result  
Player freezes and needs page reload.

## Severity  
Medium

## Status  
Open
