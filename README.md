# 可自訂直式心算練習生成器 (Customizable Vertical Mental Arithmetic Exercise Generator)

## 簡介 (Introduction)

這個網頁應用程式是一個**可自訂的直式心算練習題生成器**。它可以幫助使用者生成加減法的心算練習題，並提供答案。使用者可以自訂題目的數量、每個題目中運算的數量（例如：幾個數字相加減）、以及數字的位數範圍。

This web application is a **customizable vertical mental arithmetic exercise generator**. It helps users generate addition and subtraction mental arithmetic exercises and provides answers. Users can customize the number of questions, the number of operations in each question (e.g., how many numbers to add or subtract), and the range of digits for the numbers.

## 功能特色 (Features)

*   **自訂題目數量 (Customizable Number of Questions):**  使用者可以設定第一部分和第二部分的題目數量。
*   **自訂運算數量 (Customizable Number of Operations):** 使用者可以設定每個題目中包含的運算數量（例如：3個數字相加減，或更多）。
*   **自訂數字位數 (Customizable Number of Digits):** 使用者可以設定每個題目中數字的最小位數和最大位數，範圍從1位數到10位數。
*   **直式顯示 (Vertical Display):** 題目以直式的方式呈現，方便使用者進行心算。
*   **答案顯示/隱藏 (Show/Hide Answers):** 使用者可以選擇顯示或隱藏答案。
*   **列印功能 (Print Functionality):**  使用者可以列印題目，方便離線練習。
*   **收起/顯示選項 (Collapse/Show Options):** 使用者可以收起或顯示設定選項，以簡化介面。
*   **混合位數 (Mixed Digits):** 可以設定最小位數和最大位數不同，產生混合位數的題目。
* **多位數支援**: 支援1~10位數的加減法。

## 使用方法 (How to Use)

1.  **設定參數 (Set Parameters):**
    *   在「第一部分」和「第二部分」的設定區塊中，設定：
        *   **題數 (Number of Questions):**  要生成的題目數量。
        *   **運算數量 (Number of Operations):** 每個題目中包含的運算數量。
        *   **最小位數 (Minimum Digits):** 題目中數字的最小位數。
        *   **最大位數 (Maximum Digits):** 題目中數字的最大位數。
2.  **生成題目 (Generate Questions):** 點擊「生成新題目」按鈕。
3.  **練習 (Practice):** 進行心算練習。
4.  **顯示/隱藏答案 (Show/Hide Answers):** 點擊「顯示答案」或「隱藏答案」按鈕。
5.  **列印 (Print):** 點擊「列印題目」按鈕，將題目列印出來。
6. **收起/顯示選項**: 點擊「收起選項」或「顯示選項」按鈕。

## 程式結構 (Code Structure)

*   **`index.html`:** 網頁的主要結構，包含 HTML 元素和樣式。
*   **`style`:** 網頁的樣式，使用 CSS 進行設計。
*   **`script`:** 網頁的邏輯，使用 JavaScript 實現以下功能：
    *   `getRandomInt(min, max)`: 生成指定範圍內的隨機整數。
    *   `generateRandomNumber(minDigit, maxDigit)`: 根據位數生成隨機數。
    *   `generateExpression(numCount, minDigit, maxDigit)`: 生成加減法題目。
    *   `createVerticalExpression(nums, ops, result, showResult)`: 創建直式加減法顯示。
    *   `updateSectionTitles()`: 更新標題描述。
    *   `generateAllQuestions()`: 生成所有題目。
    *   `toggleAnswers()`: 顯示或隱藏答案。
    *   `printQuestions()`: 列印功能。
    * `hideOption()`: 收起選項。
    * `showOption()`: 顯示選項。

## 開發環境 (Development Environment)

*   **HTML5**
*   **CSS3**
*   **JavaScript**

## 貢獻 (Contributing)

歡迎任何形式的貢獻，包括但不限於：

*   回報錯誤 (Bug Reports)
*   提出新功能建議 (Feature Requests)
*   程式碼改進 (Code Improvements)

## 作者 (Author)

[Your Name/GitHub Username]

## 授權 (License)

[Choose a license, e.g., MIT License]
