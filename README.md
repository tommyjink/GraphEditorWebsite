# Graph Editor Website 📊

## Project Overview
This project is a graph theory drawing website based on HTML, CSS, and JavaScript. It utilizes the `vis.js` library to achieve graph visualization. Users can input the number of nodes and edge information of the graph on the website, and choose to draw either a directed or an undirected graph. The website will display the graph in an intuitive way.

## Project Features
### 1. User - Friendly Interaction 🤝
- It provides a clear input interface, allowing users to easily enter the number of nodes and edge information of the graph.
- There are dedicated buttons for users to choose between drawing a directed or an undirected graph, with simple and easy - to - understand operations.

### 2. Attractive Graph Display 🎨
- The `vis.js` library is used to draw graphs, with a reasonable graph layout and beautiful node and edge styles.
- Nodes are circular, with clear colors and font styles, making them easy to view and distinguish.

### 3. Intelligent Layout Algorithm 🧠
- It generates an equilateral polygon layout based on the input number of nodes, making the graph more regular and aesthetically pleasing.
- It has a physical simulation function that can automatically adjust the graph layout to achieve a stable state.

### 4. Dynamic Interaction Effects 🌟
- It supports node dragging operations, and the layout will be automatically re - balanced after dragging ends.
- It simulates node dragging animations to enhance the user experience.

## Technical Implementation
### 1. Front - End Technology Stack
- **HTML**: Constructs the page structure, including the input area and the drawing area.
- **CSS**: Designs the page style to make the page layout reasonable and beautiful.
- **JavaScript**: Implements the graph drawing logic, user interaction, and physical simulation.

### 2. Third - Party Libraries
- **vis.js**: Used for graph visualization, providing a rich set of graph and interaction functions.
- **Google Fonts**: Imports the `Indie Flower` font to make node labels more beautiful.

## Usage
### 1. Access the Website
Open the project's HTML file to enter the graph theory drawing website.

### 2. Input Graph Information
- Enter the number of nodes in the `Node Count` input box.
- Enter the edge information of the graph in the `Graph Data` text box, with each line in the format `Node 1 Node 2`, for example, `1 2`.

### 3. Select Drawing Type
- Click the `Undirected` button to draw an undirected graph.
- Click the `Directed` button to draw a directed graph.

### 4. Interaction Operations
- You can drag nodes to adjust the graph layout, and the graph will automatically re - balance after dragging ends.

## Installation and Deployment
This is a pure front - end project and does not require a complex installation process. Simply download the project files to your local machine and open the HTML file in your browser to use it.

## Notes
- The input number of nodes and edge information must meet the format requirements; otherwise, graph drawing may fail.
- Since third - party libraries are used, ensure a normal network connection to correctly load `vis.js` and Google Fonts.

## Contribution and Feedback
If you have any suggestions or find any issues with this project, feel free to submit an issue or a pull request on GitHub to make this project better! 👍
