# 🎬 Movie Watchlist APEX App

A web application built to help you discover and keep track of movies you want to watch or have already seen.  
This project leverages the power of **Oracle Cloud Infrastructure (OCI)** and the **Oracle APEX low-code platform** to deliver a seamless user experience, with movie data provided by **The Movie Database (TMDB)**.

---

## 🚀 Live Demo

You can try out the live application here:

🔗 **URL:** [Movie Watchlist APEX App](https://g6ac2036f7cec2d-rvhr0npwczbbct5t.adb.ap-singapore-1.oraclecloudapps.com/ords/r/demo/movies-watchlist/home)  
👤 **Username:** `DEMO`  
🔒 **Password:** `SecretPassw0rd`

---

## 📸 Screenshots

### 🎞️ Movie Discovery Page
Users can search for movies and view popular or upcoming titles fetched directly from the **TMDB API**.

### 🧾 Personal Watchlist
Once added, movies appear in a personal, sortable watchlist where users can track what they want to see.

---

## ✨ Key Features

- 🔍 **Browse & Search**: Dynamically search a vast library of movies from *The Movie Database* (TMDB).  
- 🎯 **Personal Watchlist**: Add and remove movies from your personalized list with a single click.  
- 🧠 **Data-Rich Interface**: View key details for each movie, including posters, release year, and ratings.  
- ⚙️ **Advanced Filtering**: Sort and filter your watchlist by title, decade, runtime, and more.

---

## 🛠️ Technology Stack

This application was built using a modern, cloud-based stack:

| Component | Technology |
|------------|-------------|
| ☁️ **Cloud Platform** | Oracle Cloud Infrastructure (OCI) |
| 🧩 **Application Framework** | Oracle APEX (low-code platform) |
| 🗄️ **Database** | Oracle Autonomous Database |
| 🎥 **External Data Source** | The Movie Database (TMDB) API |

---

## ⚙️ How It Works

1. The front-end interface is built and rendered by **Oracle APEX**.  
2. When a user searches for a movie, **APEX makes a REST API call** to the **TMDB API** to retrieve movie data.  
3. When a user adds a movie to their watchlist, its ID and associated data are **stored in the Oracle Database** on OCI.  
4. The **“My Watchlist”** page queries this local database to display the user’s curated list.

---

## 💡 Future Enhancements

- 🔐 Add user authentication and session-based watchlists.  
- ⭐ Enable rating and review features for watched movies.  
- 🧠 Include AI-based movie recommendations using viewing patterns.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

**Developed with ❤️ using Oracle APEX & OCI**
