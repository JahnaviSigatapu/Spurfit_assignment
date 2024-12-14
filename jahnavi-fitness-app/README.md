# Fitness App - Drag and Drop Chart Management

## Overview
This **Fitness App** utilizes the `react-beautiful-dnd` library to create an interactive drag-and-drop interface for managing workout charts. The app allows users to dynamically adjust workout plans by dragging bars to a chart area, adding substeps, resizing the chart, and saving progress.

### Features
1. **Drag and Drop**:
   - Implemented using the `react-beautiful-dnd` library.
   - Users can drag bars from one side and drop them into the chart area dynamically.

2. **Dynamic Chart Updates**:
   - Each bar dropped creates a new active bar below, indicating the kilometers covered.
   - Users can add substeps using an "Add Substep" button.

3. **Adaptive Scaling**:
   - Adding more bars reduces the size of bars and automatically adjusts the scale based on available width.

4. **Clear All**:
   - A "Clear All" button clears all chart data.

5. **Save Workout**:
   - The "Save Workout" button saves the workout progress.

6. **Local Storage Integration**:
   - All work progress is saved automatically in local storage whenever the chart is updated.

7. **Responsive Design**:
   - Styled with **Bootstrap** and **Material-UI** for a consistent, responsive experience across devices.

---

## Installation and Setup

### Prerequisites
- Node.js (v14 or later)
- npm or yarn package manager

### Installation Steps
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd fitness-app
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Start the development server:
   ```bash
   npm start
   # or
   yarn start
   ```

4. Open the app in your browser:
   ```
http://localhost:5173
```

### Usage
1. Drag bars from the left panel and drop them into the chart area.
2. Add substeps to the chart as needed.
3. Use the "Save Workout" button to save your progress.
4. Clear all charts using the "Clear All" button if necessary.
5. Your progress is saved automatically in local storage.

---

## Dependencies
- **React**
- **react-beautiful-dnd**
- **Bootstrap**
- **Material-UI**

### Optional Dependencies
- `prop-types` for type-checking (optional but recommended).

---

## Advantages
1. User-friendly drag-and-drop interface.
2. Fully responsive and supports all devices.
3. Automatic scaling and resizing for optimal chart management.
4. Progress is auto-saved to local storage, ensuring no data loss.

---

## Disadvantages
1. Local storage has limited capacity; data may be lost if it exceeds the limit.
2. Performance may degrade with a large number of bars or substeps.
3. Requires a modern browser to support drag-and-drop features.

---

## Deployment
The app is deployed on **Netlify** for seamless accessibility.

### Netlify Link
[Fitness App on Netlify](<insert-your-netlify-link-here>)

---

## Future Enhancements
1. Real-time collaboration features.
2. More chart customization options.

---

## Contributing
Feel free to contribute to this project by forking the repository and submitting pull requests.

---

