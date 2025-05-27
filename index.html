babel.config.js:
  1: module.exports = {
  2:   presets: [
  3:     '@babel/preset-env',
  4:     '@babel/preset-react'
  5    ]

package.json:
   2    "name": "drawing-animator",
   3:   "version": "1.0.0",
   4:   "description": "A simple drawing animation website",
   5:   "main": "src/js/app.js",
   6:   "scripts": {
   7:     "start": "webpack serve --mode development",
   8      "build": "webpack --mode production",
   9:     "test": "jest"
  10    },
  11:   "dependencies": {
  12      "react": "^18.2.0",

  14    },
  15:   "devDependencies": {
  16      "@babel/core": "^7.16.0",
  17:     "@babel/preset-env": "^7.16.4",
  18:     "@babel/preset-react": "^7.16.0",
  19      "babel-loader": "^8.2.3",
  20:     "css-loader": "^6.5.1",
  21      "html-webpack-plugin": "^5.5.0",
  22:     "jest": "^27.4.2",
  23:     "style-loader": "^3.3.1",
  24      "webpack": "^5.64.4",
  25      "webpack-cli": "^4.9.1",
  26:     "webpack-dev-server": "^4.5.0"
  27    },
  28:   "keywords": [
  29      "drawing",

  31      "react",
  32:     "canvas"
  33    ],
  34    "author": "Your Name",
  35:   "license": "MIT"
  36  }

README.md:
   1  ## Overview
   2: Drawing Animator is a web application that allows users to create drawings and animate over them. It provides a user-friendly interface with various tools for drawing and animation control.
   3  
   4: ## Features
   5: - Drawing tools: Pencil, Eraser, Shapes
   6: - Animation controls: Start, Stop, Reset
   7: - Timeline for managing animations
   8  
   9: ## Installation
  10: 1. Clone the repository:
  11     ```
  12:    git clone https://github.com/yourusername/drawing-animator.git
  13     ```

  19  
  20: 3. Install dependencies:
  21     ```
  22:    npm install
  23     ```
  24  
  25: ## Usage
  26: 1. Open `src/index.html` in your web browser.
  27: 2. Use the tools provided to create drawings.
  28: 3. Control animations using the timeline and control buttons.
  29  
  30: ## Running Tests
  31: To run the unit tests, use the following command:
  32  ```
  33: npm test
  34  ```
  35  
  36: ## License
  37: This project is licensed under the MIT License.

webpack.config.js:
   1: const path = require('path');
   2: const HtmlWebpackPlugin = require('html-webpack-plugin');
   3  
   4: module.exports = {
   5:     entry: './src/js/app.js',
   6      output: {
   7:         path: path.resolve(__dirname, 'dist'),
   8:         filename: 'bundle.js',
   9          clean: true,

  12      module: {
  13:         rules: [
  14              {
  15:                 test: /\.jsx?$/,
  16:                 exclude: /node_modules/,
  17:                 use: {
  18                      loader: 'babel-loader',

  21              {
  22:                 test: /\.css$/,
  23:                 use: ['style-loader', 'css-loader'],
  24              },

  26      },
  27:     plugins: [
  28          new HtmlWebpackPlugin({
  29:             template: './src/index.html',
  30              filename: 'index.html',

  32      ],
  33:     devServer: {
  34:         static: './dist',
  35          hot: true,
  36      },
  37:     resolve: {
  38:         extensions: ['.js', '.jsx'],
  39      },

src/index.html:
   3  <head>
   4:     <meta charset="UTF-8">
   5:     <meta name="viewport" content="width=device-width, initial-scale=1.0">
   6      <title>Drawing Animator</title>
   7:     <link rel="stylesheet" href="assets/styles/main.css">
   8:     <link rel="stylesheet" href="assets/styles/canvas.css">
   9:     <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" integrity="sha512-9usAa10IRO0HhonpyAIVpjrylPvoDwiPUiKdWk5t3PyolY1cOd4DSE0Ga+ri4AuTroPR5aQvXU9xC6qOPnzFeg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
  10  </head>
  11  <body>
  12:     <header class="app-header">
  13          <h1>Drawing Animator</h1>
  14      </header>
  15:     <main class="app-main">
  16:         <div class="tools-container">
  17:             <!-- Tools will be rendered here -->
  18          </div>
  19:         <div class="canvas-container">
  20:             <!-- Canvas will be rendered here -->
  21          </div>
  22:         <div class="timeline-container">
  23              <!-- Timeline will be rendered here -->

  25      </main>
  26:     <footer class="app-footer">
  27:         <div class="controls-container">
  28:             <!-- Controls will be rendered here -->
  29          </div>

  31      <div id="root"></div>
  32:     <script src="js/app.js" type="module"></script>
  33  </body>

src/assets/styles/canvas.css:
   1: .canvas-container {
   2:     position: relative;
   3      width: 100%;

   5      background: #fff;
   6:     box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
   7  }
   8  
   9: #drawingCanvas {
  10      width: 100%;
  11      height: 100%;
  12:     border: 2px solid #333;
  13:     border-radius: 4px;
  14:     cursor: crosshair;
  15:     touch-action: none; /* Prevents scrolling while drawing on touch devices */
  16  }
  17  
  18: .canvas-controls {
  19:     position: absolute;
  20      top: 10px;
  21      right: 10px;
  22:     display: flex;
  23      gap: 8px;
  24      background: rgba(255, 255, 255, 0.9);
  25:     border-radius: 4px;
  26  }
  27  
  28: .canvas-tools {
  29:     position: absolute;
  30      left: 10px;
  31      top: 50%;
  32:     transform: translateY(-50%);
  33:     display: flex;
  34      flex-direction: column;
  35      background: rgba(255, 255, 255, 0.9);
  36:     border-radius: 4px;
  37  }

src/assets/styles/main.css:
   2      --primary-color: #4a90e2;
   3:     --secondary-color: #f5f5f5;
   4      --text-color: #333;

  10      padding: 0;
  11:     box-sizing: border-box;
  12  }

  14  body {
  15:     font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, sans-serif;
  16      line-height: 1.6;
  17      color: var(--text-color);
  18:     background-color: var(--secondary-color);
  19  }

  21  .app-header {
  22:     display: flex;
  23:     justify-content: space-between;
  24:     align-items: center;
  25      padding: 1rem;
  26      background-color: white;
  27:     box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  28  }

  31      border: none;
  32:     border-radius: 4px;
  33      background-color: var(--primary-color);
  34      color: white;
  35:     cursor: pointer;
  36:     transition: background-color 0.2s ease;
  37  }
  38  
  39: .btn-secondary {
  40:     background-color: var(--secondary-color);
  41      color: var(--text-color);
  42:     border: 1px solid var(--border-color);
  43  }
  44  
  45: .btn-secondary:hover {
  46:     background-color: darken(var(--secondary-color), 5%);
  47  }

src/components/Canvas.js:
   1: import React, { useRef, useEffect } from 'react';
   2: import { Canvas as DrawingCanvas } from '../js/canvas';
   3  
   4: const Canvas = () => {
   5:     const canvasRef = useRef(null);
   6:     const drawingCanvas = useRef(null);
   7  
   8:     useEffect(() => {
   9:         drawingCanvas.current = new DrawingCanvas(canvasRef.current);
  10:         drawingCanvas.current.init();
  11  
  12          return () => {
  13:             drawingCanvas.current.clear();
  14          };

  16  
  17:     const handleMouseDown = (event) => {
  18:         drawingCanvas.current.startDrawing(event);
  19      };
  20  
  21:     const handleMouseMove = (event) => {
  22:         drawingCanvas.current.draw(event);
  23      };
  24  
  25:     const handleMouseUp = () => {
  26:         drawingCanvas.current.stopDrawing();
  27      };

  29      return (
  30:         <canvas
  31:             ref={canvasRef}
  32:             onMouseDown={handleMouseDown}
  33:             onMouseMove={handleMouseMove}
  34:             onMouseUp={handleMouseUp}
  35              width={800}
  36              height={600}
  37:             className="drawing-canvas"
  38          />

  41  
  42: export default Canvas;

src/components/Controls.js:
   1: import React, { useState } from 'react';
   2  
   3: const Controls = ({ onStart, onStop, onReset, onSpeedChange, onFrameSkip }) => {
   4:     const [speed, setSpeed] = useState(1);
   5:     const [isPlaying, setIsPlaying] = useState(false);
   6  
   7:     const handleSpeedChange = (e) => {
   8:         const newSpeed = parseFloat(e.target.value);
   9:         setSpeed(newSpeed);
  10:         onSpeedChange(newSpeed);
  11      };
  12  
  13:     const handlePlayPause = () => {
  14:         setIsPlaying(!isPlaying);
  15:         if (!isPlaying) {
  16:             onStart();
  17:         } else {
  18:             onStop();
  19          }

  22      return (
  23:         <div className="controls">
  24:             <div className="control-group">
  25                  <button 
  26:                     className={`btn ${isPlaying ? 'btn-secondary' : 'btn-primary'}`}
  27:                     onClick={handlePlayPause}
  28                  >
  29:                     {isPlaying ? 'Pause' : 'Play'}
  30                  </button>
  31                  <button 
  32:                     className="btn btn-secondary" 
  33:                     onClick={onReset}
  34                  >
  35:                     Reset
  36                  </button>
  37              </div>
  38:             <div className="control-group">
  39                  <label>
  40:                     Animation Speed:
  41                      <input 

  44                          max="2"
  45:                         step="0.1"
  46:                         value={speed}
  47:                         onChange={handleSpeedChange}
  48                      />
  49:                     <span>{speed}x</span>
  50                  </label>
  51              </div>
  52:             <div className="control-group">
  53                  <button 
  54:                     className="btn btn-secondary"
  55:                     onClick={() => onFrameSkip('prev')}
  56                  >
  57:                     Previous Frame
  58                  </button>
  59                  <button 
  60:                     className="btn btn-secondary"
  61:                     onClick={() => onFrameSkip('next')}
  62                  >

  69  
  70: export default Controls;

src/components/Timeline.js:
   1: import React, { useState } from 'react';
   2  
   3: const Timeline = ({ frames, currentFrame, onFrameSelect, onPlay, onPause, onReset }) => {
   4:     const [isPlaying, setIsPlaying] = useState(false);
   5  
   6:     const handlePlayPause = () => {
   7:         setIsPlaying(!isPlaying);
   8:         if (!isPlaying) {
   9              onPlay();
  10:         } else {
  11:             onPause();
  12          }

  15      return (
  16:         <div className="timeline">
  17:             <div className="timeline-controls">
  18                  <button 
  19:                     className={`btn ${isPlaying ? 'btn-secondary' : 'btn-primary'}`}
  20:                     onClick={handlePlayPause}
  21                  >
  22:                     {isPlaying ? 'Pause' : 'Play'}
  23                  </button>
  24                  <button 
  25:                     className="btn btn-secondary"
  26:                     onClick={onReset}
  27                  >
  28:                     Reset
  29                  </button>
  30              </div>
  31:             <div className="timeline-frames">
  32:                 {frames.map((frame, index) => (
  33                      <div 
  34                          key={index}
  35:                         className={`frame-item ${currentFrame === index ? 'active' : ''}`}
  36:                         onClick={() => onFrameSelect(index)}
  37                      >
  38:                         <div className="frame-preview">
  39:                             <img src={frame.thumbnail} alt={`Frame ${index + 1}`} />
  40                          </div>
  41:                         <div className="frame-info">
  42:                             <span className="frame-number">Frame {index + 1}</span>
  43:                             <span className="frame-duration">{frame.duration}ms</span>
  44                          </div>

  46                  ))}
  47:                 <div className="add-frame-btn">
  48:                     <button className="btn btn-secondary">+ Add Frame</button>
  49                  </div>
  50              </div>
  51:             <div className="timeline-scrubber">
  52                  <input 

  54                      min="0"
  55:                     max={frames.length - 1}
  56                      value={currentFrame}
  57:                     onChange={(e) => onFrameSelect(parseInt(e.target.value))}
  58                  />

src/components/Tools.js:
   1: import React, { useState } from 'react';
   2  
   3: const Tools = ({ onSelectTool, onColorChange, onSizeChange }) => {
   4:     const [selectedTool, setSelectedTool] = useState('Pencil');
   5:     const [color, setColor] = useState('#000000');
   6:     const [brushSize, setBrushSize] = useState(5);
   7  
   8:     const handleToolChange = (tool) => {
   9:         setSelectedTool(tool);
  10:         onSelectTool(tool);
  11      };
  12  
  13:     const handleColorChange = (e) => {
  14:         setColor(e.target.value);
  15          onColorChange(e.target.value);

  17  
  18:     const handleSizeChange = (e) => {
  19:         setBrushSize(e.target.value);
  20:         onSizeChange(e.target.value);
  21      };

  23      return (
  24:         <div className="tools-panel">
  25:             <div className="tool-buttons">
  26                  <button 
  27:                     className={`tool-button ${selectedTool === 'Pencil' ? 'active' : ''}`}
  28                      onClick={() => handleToolChange('Pencil')}
  29                  >
  30:                     <i className="fas fa-pencil-alt"></i>
  31                  </button>
  32                  <button 
  33:                     className={`tool-button ${selectedTool === 'Brush' ? 'active' : ''}`}
  34:                     onClick={() => handleToolChange('Brush')}
  35:                     title="Brush"
  36                  >
  37:                     <i className="fas fa-paint-brush"></i>
  38                  </button>
  39                  <button 
  40:                     className={`tool-button ${selectedTool === 'Eraser' ? 'active' : ''}`}
  41:                     onClick={() => handleToolChange('Eraser')}
  42:                     title="Eraser"
  43                  >
  44:                     <i className="fas fa-eraser"></i>
  45                  </button>
  46                  <button 
  47:                     className={`tool-button ${selectedTool === 'Fill' ? 'active' : ''}`}
  48                      onClick={() => handleToolChange('Fill')}
  49                  >
  50:                     <i className="fas fa-fill-drip"></i>
  51                  </button>
  52              </div>
  53:             <div className="tool-options">
  54:                 <div className="color-picker">
  55                      <label htmlFor="color">Color</label>

  62                  </div>
  63:                 <div className="size-slider">
  64:                     <label htmlFor="size">Size: {brushSize}px</label>
  65                      <input 
  66                          type="range" 
  67:                         id="size" 
  68                          min="1" 
  69                          max="50" 
  70:                         value={brushSize} 
  71:                         onChange={handleSizeChange} 
  72                      />

  78  
  79: export default Tools;

src/js/animation.js:
   1: class Animation {
   2:     constructor() {
   3:         this.animations = [];
   4:         this.isAnimating = false;
   5:         this.lastTime = 0;
   6:         this.currentFrame = 0;
   7:         this.fps = 24;
   8:         this.frameInterval = 1000 / this.fps;
   9:         this.frames = [];
  10:         this.loop = false;
  11      }
  12  
  13:     start() {
  14:         if (!this.isAnimating) {
  15:             this.isAnimating = true;
  16:             this.lastTime = performance.now();
  17:             this.animate();
  18          }

  20  
  21:     stop() {
  22:         this.isAnimating = false;
  23      }

  25      animate() {
  26:         if (!this.isAnimating) return;
  27  
  28:         const currentTime = performance.now();
  29:         const deltaTime = currentTime - this.lastTime;
  30  
  31:         if (deltaTime >= this.frameInterval) {
  32:             this.update(deltaTime);
  33:             this.lastTime = currentTime - (deltaTime % this.frameInterval);
  34  
  35:             this.currentFrame++;
  36:             if (this.currentFrame >= this.frames.length) {
  37:                 if (this.loop) {
  38:                     this.currentFrame = 0;
  39:                 } else {
  40:                     this.stop();
  41                      return;

  45  
  46:         requestAnimationFrame(this.animate.bind(this));
  47      }

  49      update(deltaTime) {
  50:         if (this.frames[this.currentFrame]) {
  51:             this.animations.forEach(animation => {
  52:                 animation.update(deltaTime, this.frames[this.currentFrame]);
  53              });

  57      addFrame(frameData) {
  58:         this.frames.push(frameData);
  59      }

  61      removeFrame(index) {
  62:         this.frames.splice(index, 1);
  63      }

  65      add(animation) {
  66:         this.animations.push(animation);
  67      }

  69      remove(animation) {
  70:         this.animations = this.animations.filter(a => a !== animation);
  71      }
  72  
  73:     setFPS(fps) {
  74:         this.fps = fps;
  75:         this.frameInterval = 1000 / fps;
  76      }
  77  
  78:     setLoop(loop) {
  79:         this.loop = loop;
  80      }

  82      getCurrentFrame() {
  83:         return this.frames[this.currentFrame];
  84      }
  85  
  86:     getTotalFrames() {
  87:         return this.frames.length;
  88      }
  89  
  90:     reset() {
  91:         this.currentFrame = 0;
  92:         this.lastTime = performance.now();
  93      }

src/js/app.js:
   1: import React, { useState, useRef, useEffect } from 'react';
   2  import ReactDOM from 'react-dom/client';
   3: import Canvas from '../components/Canvas';
   4: import Tools from '../components/Tools';
   5: import Timeline from '../components/Timeline';
   6: import Controls from '../components/Controls';
   7  import Animation from './animation';
   8  
   9: const App = () => {
  10:     const [selectedTool, setSelectedTool] = useState('Pencil');
  11:     const [color, setColor] = useState('#000000');
  12:     const [brushSize, setBrushSize] = useState(5);
  13:     const [frames, setFrames] = useState([]);
  14:     const [currentFrame, setCurrentFrame] = useState(0);
  15  
  16:     const canvasRef = useRef(null);
  17:     const animationRef = useRef(new Animation());
  18  
  19:     useEffect(() => {
  20          // Initialization code here

  22  
  23:     const handleToolSelect = (tool) => {
  24:         setSelectedTool(tool);
  25      };
  26  
  27:     const handleColorChange = (newColor) => {
  28:         setColor(newColor);
  29      };
  30  
  31:     const handleSizeChange = (newSize) => {
  32:         setBrushSize(newSize);
  33      };
  34  
  35:     const handlePlay = () => {
  36:         animationRef.current.start();
  37      };
  38  
  39:     const handlePause = () => {
  40:         animationRef.current.stop();
  41      };
  42  
  43:     const handleReset = () => {
  44:         animationRef.current.reset();
  45:         setCurrentFrame(0);
  46      };
  47  
  48:     const handleFrameSelect = (frameIndex) => {
  49:         setCurrentFrame(frameIndex);
  50      };
  51  
  52:     const handleFrameSkip = (direction) => {
  53          if (direction === 'next') {
  54:             setCurrentFrame((prevFrame) => Math.min(prevFrame + 1, frames.length - 1));
  55:         } else if (direction === 'prev') {
  56:             setCurrentFrame((prevFrame) => Math.max(prevFrame - 1, 0));
  57          }

  60      return (
  61:         <div className="app">
  62:             <header className="app-header">
  63                  <h1>Drawing Animator</h1>
  64              </header>
  65:             <main className="app-main">
  66:                 <Tools 
  67:                     onSelectTool={handleToolSelect}
  68                      onColorChange={handleColorChange}
  69:                     onSizeChange={handleSizeChange}
  70                  />
  71:                 <Canvas ref={canvasRef} />
  72                  <Timeline 
  73:                     frames={frames}
  74                      currentFrame={currentFrame}
  75:                     onFrameSelect={handleFrameSelect}
  76                      onPlay={handlePlay}
  77:                     onPause={handlePause}
  78:                     onReset={handleReset}
  79                  />
  80              </main>
  81:             <footer className="app-footer">
  82:                 <Controls 
  83:                     onStart={handlePlay}
  84:                     onStop={handlePause}
  85:                     onReset={handleReset}
  86:                     onSpeedChange={() => {}}
  87:                     onFrameSkip={handleFrameSkip}
  88                  />

  93  
  94: const root = ReactDOM.createRoot(document.getElementById('root'));
  95  root.render(<App />);

src/js/canvas.js:
   1: class Canvas {
   2:     constructor(canvasElement) {
   3:         this.canvas = canvasElement;
   4:         this.ctx = this.canvas.getContext('2d');
   5:         this.drawing = false;
   6:         this.lastX = 0;
   7:         this.lastY = 0;
   8:         this.color = '#000000';
   9:         this.size = 5;
  10:         this.tool = 'Pencil';
  11      }

  13      init() {
  14:         this.canvas.width = 800;
  15:         this.canvas.height = 600;
  16:         this.clear();
  17      }
  18  
  19:     startDrawing(e) {
  20:         this.drawing = true;
  21:         this.lastX = e.offsetX;
  22:         this.lastY = e.offsetY;
  23      }

  25      draw(e) {
  26:         if (!this.drawing) return;
  27:         this.ctx.strokeStyle = this.color;
  28:         this.ctx.lineWidth = this.size;
  29:         this.ctx.lineCap = 'round';
  30:         this.ctx.beginPath();
  31:         this.ctx.moveTo(this.lastX, this.lastY);
  32:         this.ctx.lineTo(e.offsetX, e.offsetY);
  33:         this.ctx.stroke();
  34:         this.lastX = e.offsetX;
  35:         this.lastY = e.offsetY;
  36      }
  37  
  38:     stopDrawing() {
  39:         this.drawing = false;
  40      }

  42      clear() {
  43:         this.ctx.fillStyle = 'white';
  44:         this.ctx.fillRect(0, 0, this.canvas.width, this.canvas.height);
  45      }
  46  
  47:     setColor(color) {
  48:         this.color = color;
  49      }
  50  
  51:     setSize(size) {
  52:         this.size = size;
  53      }
  54  
  55:     setTool(tool) {
  56:         this.tool = tool;
  57      }

  59  
  60: export default Canvas;

src/js/tools.js:
   1: export function initTools(canvas) {
   2:     const pencilButton = document.getElementById('pencil');
   3:     const eraserButton = document.getElementById('eraser');
   4:     const colorPicker = document.getElementById('colorPicker');
   5:     const brushSize = document.getElementById('brushSize');
   6  
   7:     pencilButton.addEventListener('click', () => {
   8:         canvas.setTool('Pencil');
   9      });
  10  
  11:     eraserButton.addEventListener('click', () => {
  12:         canvas.setTool('Eraser');
  13      });
  14  
  15:     colorPicker.addEventListener('input', (e) => {
  16:         canvas.setColor(e.target.value);
  17      });
  18  
  19:     brushSize.addEventListener('input', (e) => {
  20:         canvas.setSize(e.target.value);
  21      });

  23      return {
  24:         setPencil: () => {
  25:             canvas.setTool('Pencil');
  26          },
  27:         setEraser: () => {
  28:             canvas.setTool('Eraser');
  29          },
  30:         setColor: (color) => {
  31:             canvas.setColor(color);
  32          },
  33:         setSize: (size) => {
  34:             canvas.setSize(size);
  35          }

tests/canvas.test.js:
   1: import { Canvas } from '../src/js/canvas';
   2  
   3: describe('Canvas', () => {
   4:     let canvas;
   5:     let canvasElement;
   6      let ctx;

   8      beforeEach(() => {
   9:         canvasElement = document.createElement('canvas');
  10:         canvasElement.width = 800;
  11:         canvasElement.height = 600;
  12:         ctx = canvasElement.getContext('2d');
  13:         canvas = new Canvas(canvasElement);
  14      });
  15  
  16:     test('should initialize canvas with correct dimensions', () => {
  17:         canvas.init();
  18:         expect(canvasElement.width).toBe(800);
  19:         expect(canvasElement.height).toBe(600);
  20      });
  21  
  22:     test('should clear the canvas', () => {
  23:         // Draw something on the canvas
  24:         ctx.fillStyle = 'black';
  25          ctx.fillRect(0, 0, 100, 100);
  26  
  27:         // Clear the canvas
  28:         canvas.clear();
  29  
  30:         // Check if the canvas is cleared
  31:         const imageData = ctx.getImageData(0, 0, canvasElement.width, canvasElement.height);
  32:         const data = imageData.data;
  33          let allWhite = true;

  36              if (data[i] !== 255 || data[i + 1] !== 255 || data[i + 2] !== 255) {
  37:                 allWhite = false;
  38                  break;

  43  
  44:     test('should set the color', () => {
  45:         canvas.setColor('red');
  46:         expect(canvas.color).toBe('red');
  47      });
  48  
  49:     test('should set the size', () => {
  50:         canvas.setSize(10);
  51:         expect(canvas.size).toBe(10);
  52      });
  53  
  54:     test('should set the tool', () => {
  55:         canvas.setTool('eraser');
  56:         expect(canvas.tool).toBe('eraser');
  57      });
