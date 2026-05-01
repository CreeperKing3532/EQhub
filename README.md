# Steam Manifest API

A free and simple API for accessing Steam manifest files, organized by Steam App ID.

## 🚀 Overview

This project provides an easy way to download Steam manifest files for any Steam game using its App ID.  
Each game is stored on its own branch, named after the Steam App ID.

Example:
- Portal → App ID `400` → branch `400`

## 📦 How It Works

Every Steam game is mapped to a Git branch using its App ID.

To download a manifest, use:

archive/refs/heads/{appid}.zip

### Example

Portal (App ID 400):

archive/refs/heads/400.zip

## 🧠 Use Cases

- Game modding and research  
- Steam manifest archival  
- Version tracking and analysis  
- Automation tools requiring manifest data  

## ⚙️ Usage

1. Find the Steam App ID of the game  
2. Replace `{appid}` in the endpoint  
3. Download the corresponding `.zip` archive  

## ❗ Notes

- This API is provided for free use  
- Availability of manifests may vary by game  
- Data is organized strictly by Steam App ID  
- No guarantee of completeness or updates  

## 🔮 Future Improvements

- Automated manifest updates  
- Game name search (instead of App ID)  
- Metadata endpoints  
- Optional API key / rate limiting system  

## 📜 License

This project is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0).

You are free to:
- Use  
- Share  
- Modify  
- Distribute  

As long as proper attribution is given.
