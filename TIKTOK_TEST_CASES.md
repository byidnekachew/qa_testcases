# TikTok Video Upload - Test Cases



## Test Case 1  
**Test Case ID:** TC_UPLOAD_001  
**Title:** Checks that private videos are only availible to the author  
**Requirement:** The application should allow users to select a privacy level for their videos.  
**Test type:** Positive  
**Preconditions:**
- User is logged in and has uploaded a video to their page
- At least one video is set to public or friends
- User has navigated to their own page

**Test steps:**
1. Tap the video in order to open it
2. Tap the "three-dots" icon to open the additional options menu
3. Tap the "Set video to private" option
4. Wait until a message pops up saying the video has been set to private
5. Verify that the authoring user can watch the video
6. Log out of the authoring account and then log in to another account
7. Navigate to the authoring user's page
8. Verify that the video does not appear

**Test Data:**
- Author's Username: @creator_test
- Viewer's Username: @viewer_test

**Expected Result:**
- Video appears for and can be watched by author
- Video does not exist for viewer

**Priority:** Medium  


## Test Case 2  
**Test Case ID:** TC_UPLOAD_002  
**Title:** Checks that videos uploaded to Friends feed are only availible to the author's friends  
**Requirement:** The application should allow users to select a privacy level for their videos.  
**Test type:** Positive  
**Preconditions:**
- User is logged in and has uploaded a video to their page
- At least one video is set to public or private
- User has navigated to their own page
- User should have an existing Close Friends list

**Test steps:**
1. Tap the video in order to open it
2. Tap the "three-dots" icon to open the additional options menu
3. Tap the "Make video availible only to friends" option
4. Wait until a message pops up saying the video has been set to be availible only to friends
5. Verify that the authoring user can watch the video
6. Log out of the authoring account and then log in to a friend's account
7. Navigate to the authoring user's page
8. Verify that the friend user can see and watch the video
9. Log out of the friend's account and log in to a random viewer's account
10. Verify that the video does not appear

**Test Data:**
- Author's Username: @creator_test
- Viewer's Username: @viewer_test
- Friends' Username: @friend_test

**Expected Result:**
- Video appears for and can be watched by author
- Video appears for and can be watched by friend
- Video does not exist for viewer

**Priority:** Low  


## Test Case 3  
**Test Case ID:** TC_UPLOAD_003 
**Title:** Checks that caption can be entered when within the acceptable length  
**Requirement:** The application requires that a video's caption, if present, has 2200 characters max  
**Test type:** Boundary Test  
**Preconditions:**
- The user is logged in and navigated to the upload page
- The user has uploaded a valid video
- Acceptable characters and content are being used for the caption

**Test steps:**
1. Tap the upload button, select a video to upload, and go through the proper steps to upload a video
2. Once reaching the caption page, type in a caption of length 2199 characters
3. Select next and finish confirming the post
4. Wait for the video to load and navigate to the authoring user's page
5. Verify the caption is present after clicking the test video

**Test Data:**
- Caption text: test captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontes

**Expected Result:**
- The caption text appears
- The user can click to expand the caption and view the whole thing rather than the first few characters only

**Priority:** Medium  


## Test Case 4  
**Test Case ID:** TC_UPLOAD_004  
**Title:** Checks that an excessively long caption cannot be entered and posted  
**Requirement:** The application requires that a video's caption, if present, has 2200 characters max  
**Test type:** Boundary Test  
**Preconditions:**
- The user is logged in and navigated to the upload page
- The user has uploaded a valid video
- Acceptable characters and content are being used for the caption

**Test steps:**
1. Tap the upload button, select a video to upload, and go through the proper steps to upload a video
2. Once reaching the caption page, type in a caption of length 2201 characters
3. Select next and attempt to finish confirming the post
4. At this point, terminate the test regardless of outcome by exiting the application

**Test Data:**
- Caption text: test captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest captiontest1

**Expected Result:**
- An error message should appear, prompting the user to reduce the length of the caption
- The video should not be posted

**Priority:** Medium  


## Test Case 5  
**Test Case ID:** TC_UPLOAD_005  
**Title:** Checks that too many hashtags cannot be used on a post  
**Requirement:** The application requires that a maximum of 30 captions can be used  
**Test type:** Edge Case  
**Preconditions:**
- The user is logged in and navigated to the upload page
- The user has uploaded a valid video
- Acceptable characters and content are being used for the hashtags
- The hashtags entered are an apropriate length 

**Test steps:**
1. Tap the upload button, select a video to upload, and go through the proper steps to upload a video
2. Once reaching the hashtags page, start entering captions until you have entered 31
3. Select next and attempt to finish confirming the post
4. At this point, terminate the test regardless of outcome by exiting the application

**Test Data:**
- Hashtags text: #test_1; #test_2; #test_3; ...

**Expected Result:**
- An error message should appear, prompting the user to reduce the number of captions used
- The video should not be posted

**Priority:** Medium  


## Test Case 6  
**Test Case ID:** TC_UPLOAD_006  
**Title:** Checks that a video upload isn't too large  
**Requirement:** The application requires that a video be at most 287MB  
**Test type:** Edge Case  
**Preconditions:**
- The user is logged in and navigated to the upload page
- The user is attempting to upload a video of a valid format
- The video is present on the uploading device

**Test steps:**
1. Tap the upload button
2. Select the video "test_toolarge.mp4"
3. Select next and attempt to complete the file upload process
4. Wait for it to load then terminate the test regardless of result

**Test Data:**
- File name: test_toolarge.mp4
- File type: mp4
- Size: 288MB
- Resolution: 1080x1920
- Aspect Ratio: 9:16

**Expected Result:**
- The video should not attempt to upload as it is too large and could jeopardize the application
- An error message should display indicating that the specific video cannot be uploaded
- The user should be prompted to upload another video

**Priority:** High  


## Test Case 7  
**Test Case ID:** TC_UPLOAD_007  
**Title:** Checks that video is not too short  
**Requirement:** An uploaded video should be at least 3 seconds  
**Test type:** Negative test  
**Preconditions:**
- The user is logged in and navigated to the upload page
- The user is attempting to upload a video of a valid format
- The video is present on the uploading device

**Test steps:**
1. Tap the upload button
2. Select the video "test_tooshort.mp4"
3. Select next and attempt to complete the file upload process
4. Wait for it to load then terminate the test regardless of result

**Test Data:**
- File name: test_tooshort.mp4
- File type: mp4
- Length: 2 seconds
- Resolution: 1080x1920
- Aspect Ratio: 9:16

**Expected Result:**
- The video should attempt to upload and fail given that it is too short
- An error message should display indicating that the specific video cannot be uploaded
- The user should be prompted to upload another video

**Priority:** Medium  


## Test Case 8  
**Test Case ID:** TC_UPLOAD_008  
**Title:** Checks for profane content in caption  
**Requirement:** Prohibited/inappropriate content should not be allowed in a post  
**Test type:** Negative test  
**Preconditions:**
- The user is logged in and navigated to the upload page
- The user has uploaded a valid video
- Acceptable characters and content are being used for the caption

**Test steps:**
1. Tap the upload button, select a video to upload, and go through the proper steps to upload a video
2. Once reaching the caption page, type in a caption containing profanity
3. Select next and attempt to finish confirming the post
4. At this point, terminate the test regardless of outcome by exiting the application  

**Test Data:**
- Caption text: The darn test caption

**Expected Result:**
- An error message should appear telling the user that their post was unsucessful due to policy against content guidelines
- The user should be unable to post any other content for 6 hours

**Priority:** High  


## Test Case 9  
**Test Case ID:** TC_UPLOAD_009  
**Title:** Deny videos in landscape orientation  
**Requirement:** All videos uploaded to the application should be in portrait orientation 
**Test type:** Black box  
**Preconditions:**
- The user is logged in and navigated to the upload page
- The user is attempting to upload a video of a valid format
- The video is present on the uploading device

**Test steps:**
1. Tap the upload button
2. Select the video "test_landscape.mp4"
3. Select next and attempt to complete the file upload process
4. Wait for it to load then terminate the test regardless of result

**Test Data:**
- File name: test_landscape.mp4
- File type: mp4
- Length: 25 seconds
- Resolution: 1920x1080
- Aspect Ratio: 16:9

**Expected Result:**
- The video should attempt to upload and fail given that it is in the wrong orientation
- An error message should display indicating that the specific video cannot be uploaded
- The user should be prompted to upload another video

**Priority:** Low  


## Test Case 10  
**Test Case ID:** TC_UPLOAD_010  
**Title:** Check if images are being uploaded  
**Requirement:** Files uploaded for posts should only be in specific video file formats  
**Test type:** Black box  
**Preconditions:**
- The user is logged in and navigated to the upload page
- The file is present on the uploading device

**Test steps:**
1. Tap the upload button
2. Navigate through the file explorer and search for images

**Test Data:**
- N/A

**Expected Result:**
- No images should be found in the file explorer/library
- Images and non-videos should be excluded by the system

**Priority:** High  
