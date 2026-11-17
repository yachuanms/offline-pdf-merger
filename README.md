# Offline PDF Merger｜離線 PDF 合併工具

一款簡單的 Windows 桌面工具，將多份 PDF 按照指定順序合併成一份。所有檔案皆在本機處理，不需連網或上傳。

A simple Windows desktop tool that combines multiple PDFs in your preferred order. All files are processed locally, with no internet connection or uploads required.

## 功能 Features

- 加入多份 PDF，並調整合併順序。
  Add multiple PDFs and rearrange their order.
- 移除選取檔案或清空清單。
  Remove selected files or clear the list.
- 合併所有頁面，並選擇輸出位置。
  Merge all pages and choose where to save the result.
- 完成後快速開啟輸出資料夾。
  Open the output folder after merging.
- 全程離線，無需安裝 Python。
  Works offline. No Python installation required.

## 下載與使用 Download & Usage

1. 前往本專案的 **Releases** 頁面。
   Go to this repository’s **Releases** page.
2. 下載 `OfflinePDFMerger.exe`。
   Download `OfflinePDFMerger.exe`.
3. 雙擊開啟程式。
   Double-click to launch.
4. 點選「加入 PDF」，選擇至少兩份檔案。
   Click “加入 PDF” to select at least two files.
5. 使用「上移／下移」調整順序。
   Use “上移／下移” to reorder the files.
6. 點選「合併並另存」，選擇檔名與儲存位置。
   Click “合併並另存” to choose an output filename and location.

> 目前介面為繁體中文，適用於 Windows。
> The interface is currently in Traditional Chinese. Windows only.

## 隱私 Privacy

本工具不會上傳 PDF，也不需要帳號或網路連線。來源檔案不會被修改。

This tool does not upload your PDFs and requires no account or internet connection. Source files are not modified.

## 注意事項 Limitations

- 需要開啟密碼的 PDF，請先解除密碼保護。
  PDFs that require an opening password must be unlocked first.
- 有加密標記但不需要開啟密碼的 PDF，程式會嘗試讀取。
  PDFs with encryption but no opening password will be read when supported.
- 合併後的文件不會保留原有數位簽章的有效性。
  Digital signatures from the original documents will not remain valid in the merged file.
- 互動表單、附件及複雜書籤不保證完整保留。
  Interactive forms, attachments, and complex bookmarks may not be fully preserved.
- 較大的 PDF 可能需要更多處理時間與記憶體。
  Large PDFs may require more processing time and memory.

## 技術 Built With

Python · Tkinter · pypdf · PyInstaller
