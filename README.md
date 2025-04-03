# Reading App

# Proksi Reading App – Swift Test Case (Partial Implementation)

This repository contains a **partial implementation** of the Swift position test case provided by Proksi Yazılım. The test goal was to build a reading app with both text and audio features, based on a Figma design and a Swagger-documented API.

I focused on delivering a solid **UI and reading experience** with integrated **API functionality**, and chose not to implement audio and advanced transcript sync features due to the test’s wide scope.

---

## ✅ What’s Implemented

- 🎨 **UI based on Figma**
  - Reading screen with clean layout
  - Pagination of paragraphs for smooth reading

- 🔌 **API Integration**
  - Integrated 4 endpoints from the provided Swagger docs:
    - `GET /books`
    - `GET /book/:id`
    - `GET /metadata/:id`
    - `GET /transcript/:id`
  - Live data used for loading books, metadata, and content

- **Reading Mode**
  - Paginated paragraph display using API-fetched content

---


## 🎬 Demo Video:

![testcase](https://github.com/user-attachments/assets/802e422c-6715-4cfd-afa2-410aabd36264)

- [Demo Video](https://www.dropbox.com/scl/fi/us7hjtlhdk32wao8c3dbl/testcase.MP4?rlkey=0v8acb46nkdgz6ksbnarsnbbv&st=6g5rky00&raw=1)


---

## ❌ What’s Not Implemented

- Audio playback and player UI (*can be done with AVPlayer*)
- Transcript highlighting & synchronization (*can be synchronized with the start and end data fields*)
- Rewind functionality (*can be implemented with start and end data fields*)
- Customization options (font size, background color) (*Background is provided with state logics*)

---

## ⚙️ How to Run

1. Clone the repo
2. Open `.xcodeproj` or `.xcworkspace` in Xcode
3. Run on a Simulator or Device

---

## 📝 Notes

This project was treated as a **time-limited technical assessment**. I focused on:
- Clean UI implementation
- Real API integration
- Code structure that is easy to scale and maintain

The current codebase is **cleanly designed, modular, and open for further development**. If needed, audio and customization features can be integrated into the current structure without major refactoring.

---

## 💬 Final Thoughts

While I didn’t implement the full feature set, I believe this submission demonstrates my capabilities in Swift, API integration, and clean UI development. I’d be happy to discuss the architecture and walk through next steps for further development.

Thanks for reviewing!
