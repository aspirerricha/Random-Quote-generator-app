# Random Quote Generator 

I've always loved collecting quotes that stick with me , this Flutter app pulls a random quote from a live quotes API every time you tap the button.

## Overview

Initially I built this application as a hardcoded list of quotes .It has now evolved into
a live app pulling from a public quotes API.

## Features

- **Live quotes** — pulls from a public quotes API instead of a fixed list
- **One tap, new quote** — the "Inspire me" button surfaces a new quote instantly
- **Custom visual identity** — deep ink-green background, warm brass accent,
  serif typography for the quote text, and a soft author line
- **Graceful failure handling** — shows a clear message instead of crashing
  if the network is unavailable or the API is down

## Design decisions

- **Color palette** — I used a dark green ink colour for the background and paired it with a warm yellow used for the button and the author line. The idea was to make it feel
  like the inside cover of a journal.
- **Typography** — Used lora font from Googlefonts for quotes and inter for the author

## Tech stack

- **Flutter** — UI and state management (`StatefulWidget`)
- **http** package — fetching quotes from a public API
- **dart:convert** — parsing the JSON response

## Setup

1. Clone this repo
2. Install dependencies:
   ```
   flutter pub get
   ```
3. Run the app:
   ```
   flutter run
   ```

## Screenshot

_Add your screenshot here before uploading to GitHub._

```
<img width="720" height="1600" alt="image" src="https://github.com/user-attachments/assets/1d4fc0c9-0ca2-4bec-80f9-aaf8e11433c4" />

```
