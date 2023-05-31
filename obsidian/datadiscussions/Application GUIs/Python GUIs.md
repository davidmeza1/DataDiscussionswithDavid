𝐇𝐞𝐫𝐞 𝐚𝐫𝐞 𝐚𝐥𝐥 𝐭𝐡𝐞 𝐥𝐢𝐛𝐫𝐚𝐫𝐢𝐞𝐬 𝐭𝐡𝐚𝐭 𝐈 𝐜𝐨𝐮𝐥𝐝 𝐟𝐢𝐧𝐝 𝐟𝐨𝐫 𝐛𝐮𝐢𝐥𝐝𝐢𝐧𝐠 𝐆𝐔𝐈𝐬 𝐰𝐢𝐭𝐡 𝐏𝐲𝐭𝐡𝐨𝐧:  

📚 [ShHiny for Python](https://shiny.rstudio.com/py/)

Shiny makes it easy to build interactive web applications with the power of Python’s data and scientific stack.

-   **Approachable**: Write your application in Python; no web development skills required.
-   **Flexible**: Built from the ground up to support custom layouts, styles, and the modularity required for full-fledged applications, all from Python.
-   **Performant**: Uses reactivity to efficiently handle data processing and minimize expensive re-computations.

Steps Used to create and run shiny python apps from VS code
https://shiny.rstudio.com/py/docs/install.html#configure-visual-studio-code

# Installing Shiny for Python

To install Shiny for Python, first create a new directory for your first Shiny app, and change to it.

```
mkdir myapp
cd myapp
```

If you want to use a virtual environment, feel free to create/activate one now:

```
# Create a virtual environment in the .venv subdirectory
python3 -m venv venv

# Activate the virtual environment
source venv/bin/activate
```

It is also a good idea to upgrade `pip` and install `wheel`:

```
pip install --upgrade pip wheel
```

Next, install `shiny` from PyPI.

```
pip install shiny
```

You may on occasion need to force installation of updated versions of our packages, since they are in development. This can be done with:

```
pip install --upgrade shiny htmltools
```

## Running[](https://shiny.rstudio.com/py/docs/install.html#running)

In the same directory you created above, run:

```
shiny create .
```

This will create a basic Shiny application in the current directory, in a file named `app.py`.

To run the app, run this command from the shell:

```
shiny run --reload
```

This should start your app and also automatically launch a web browser.

The `--reload` flag means that file changes in the current directory tree will cause the Python process to restart and the browser to reload. So your workflow is 1) save changes to `app.py`, 2) wait a moment for the changes to appear in the browser.

## [Install Shiny for Python extension](https://marketplace.visualstudio.com/items?itemName=posit.shiny-python)



📚[Streamlit](https://streamlit.io/)  
  
Pre-built components that interacts with machine learning models without having to write HTML, CSS, or JavaScript code.  
  
  
📚Tkinter Designer  
  
It's a great tool to prototype your ideas in a very short time. Since it uses OS native elements,it is relatively easy to learn and implement but no advanced widgets.  
  
📚PyQT  
  
Great for Rapid prototyping and Code reusability but has a Steep learning curve and Limited documentation.  
  
📚Gradio  
  
It creates custom machine learning models with user-friendly interfaces.  
  
📚Kivy  
  
Supports multi-touch input and Easy to learn for beginners but Slower performance and Limited GUI widgets.  
  
📚Voila  
  
Converting Jupyter notebooks into standalone interactive web applications.  
  
📚CherryPy  
  
A lightweight web framework that is designed to be and easy to use including a built-in web server.  
  
📚wxPython  
  
Rich GUI features and Good integration with other libraries. But code can become verbose and complex for large application with compatibility issues.  
  
📚PySide  
  
A Python binding for the Qt framework but Limited third-party library support and additional costs.  
  
📚PyGTK  
  
More advanced features, such as multi-touch input or 3D graphics but require more code.  
  
📚PyForms  
  
Provides a drag-and-drop GUI editor for rapid prototyping But Can have performance issues with larger and more complex GUIs.  
  
📚PySimpleGUI  
  
Provides a simple and intuitive API for creating GUIs with minimal code but limited flexibility and customization options.  
  
📚Toga  
  
Provides a consistent API across multiple platforms but Limited GUI widgets.  
  
📚PyGObject  
  
Good documentation and community support but Can have compatibility issues with some Python versions and platforms.  
  
📚Panel  
  
A powerful open-source Python library that allows developers to create rich and interactive web-based dashboards and applications.  
  
📚PyVista  
  
3D plotting and mesh analysis through a streamlined interface for the Visualization Toolkit (VTK).  
  
📚PySDL2  
  
A set of Python bindings for the SDL2 multimedia library.  
  
📚Eel  
  
A little Python library for making simple Electron-like HTML/JS GUI apps.  
  
📚Flexx  
  
A pure Python toolkit for creating GUIs, that uses web technology for rendering.  
  
📚Pybee  
  
A collection of Python-to-native compilers for creating mobile and desktop apps.  
  
📚Dash  
  
📚Flask

[PyGUbu](https://github.com/alejandroautalan/pygubu)
