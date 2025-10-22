# Project 4 - TriviaTime

Submitted by: **Gerald Shimo**

**TriviaTime** is an iOS app that fetches trivia questions from the [Open Trivia Database API](https://opentdb.com/api.php?amount=10&category=18) and allows users to test their knowledge by answering a series of questions. The app displays multiple-choice and true/false questions, keeps track of scores, and allows users to reset the game for a new set of questions.

Time spent: **7** hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] User can view and answer at least 5 trivia questions.
- [x] App retrieves question data from the Open Trivia Database API.
- [x] Fetches a different set of questions when the user resets the game.
- [x] User can see their score after answering all questions.
- [x] True/False questions only show two answer options.

## Optional Features

The following **optional** features are implemented:

- [ ] User can choose a specific category of questions.
- [ ] User receives feedback after each question, showing whether their answer was correct before proceeding.

## Additional Features

- [ ] Added a gradient background for improved UI design.
- [ ] Implemented smooth animations between questions.
- [ ] Improved data handling to prevent repeated options from previous questions.
- [ ] Responsive layout that adjusts well to various screen sizes.

## Video Walkthrough


[Guide]]
<div>
    <a href="https://www.loom.com/share/62d0f9c8cbe245fda6b4cbc20a9f12cc">
      <p>Videos | Library | Loom - 21 October 2025 - Watch Video</p>
    </a>
    <a href="https://www.loom.com/share/62d0f9c8cbe245fda6b4cbc20a9f12cc">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/62d0f9c8cbe245fda6b4cbc20a9f12cc-a5899594d62a31c7-full-play.gif">
    </a>
</div>

*(Click the image to watch the walkthrough video on Loom)*

## Notes

Some challenges included:
- Handling HTML entities in API responses (e.g., `&quot;` instead of `"`)
- Ensuring true/false questions display only two options
- Preventing leftover options from previous questions when fetching new ones

## License

    Copyright 2025 Gerald Shimo

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
