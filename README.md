# 🎵 Audio Tempo Doubler

Double the speed of your audio files **without changing the voice**. 100% local processing, no server needed.

## ✨ Features

- **2x Tempo** - Your audio plays 2 times faster
- **Pitch unchanged** - Voices stay normal (no chipmunk effect)
- **Local processing** - Everything happens in your browser, your files never leave your computer
- **MP3 320kbps export** - Lightweight files with great quality
- **Batch processing** - Process multiple audio files at once
- **Mobile-friendly** - Works perfectly on smartphones and tablets
- **No account needed** - Use directly, no sign-up required

## 🚀 Usage

### Online

Simply go to: **[https://your-domain.com/audio-tempo-doubler.html]()**

### Locally

1. Download `audio-tempo-doubler.html`
2. Double-click to open it in your browser
3. Ready to go!

## 📋 How it works

1. **Select your files** - Click or drag-and-drop your audio files
2. **Hit "Process"** - FFmpeg does the magic in your browser
3. **Download results** - Files download automatically

That's it! 🎉

## 📁 Supported formats

- MP3
- WAV
- OGG
- FLAC
- M4A
- AAC

## 🌐 Host on GitHub Pages

## 🔧 Technology

- **FFmpeg.wasm** - Audio processing via WebAssembly
- **Vanilla JavaScript** - No external dependencies
- **HTML5 Audio API** - File handling
- **CSS3** - Responsive interface

## 🎛️ Customization

### Change speed

Open the HTML file and modify this line:

```javascript
'-filter:a', 'atempo=2.0',  // Change 2.0 to another value
```

Examples:
- `1.5` = 50% faster
- `2.0` = 2x faster ⭐ (default)
- `3.0` = 3x faster

### Change MP3 quality

Modify this line:

```javascript
'-b:a', '320k',  // Change 320k to another value
```

Examples:
- `128k` = smaller files, lower quality
- `192k` = good balance
- `320k` = best quality ⭐ (default)

## 📦 Download

Just grab the `audio-tempo-doubler.html` file and you're ready!

No installation, no dependencies. Your browser does everything.

## 🌍 Compatible with

- Chrome/Edge (all OS)
- Firefox (all OS)
- Safari (Mac/iOS)
- Opera
- All modern browsers

## ⚡ Performance

- **Loading**: ~20-30 seconds first time (FFmpeg loads)
- **Processing**: Depends on file size
  - 1 min audio = ~5-10 seconds
  - 5 min audio = ~20-30 seconds
  - 10 min audio = ~40-60 seconds

Larger files take longer, that's normal! ⏳

## 🔒 Privacy

✅ **Your files stay on your computer**
✅ **Zero data sent** to any server
✅ **No ads, no tracking**
✅ **Works offline** after initial load

## 🎓 Use cases

- Speed up videos/podcasts to save time
- Create accelerated versions of music
- Adjust composition duration
- Test BPMs without changing pitch
- And more! 🎵

## 🐛 Having issues?

### "FFmpeg won't load"
- Refresh the page
- Clear browser cache
- Try another browser

### "File isn't processing"
- Make sure the file is a valid audio format
- Try a smaller file first
- Check console (F12) for errors

### "It's slow"
- That's normal, audio processing takes time
- Larger files take longer
- Your computer is doing all the work!

## 📝 License

Free to use. FFmpeg is licensed under LGPL.

## 🙌 Thanks!

Enjoy your doubled tempo! 🚀

---

**Need help?** Create an issue or contact me.

**Like it?** Share the link! 💙