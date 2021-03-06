## [Streamlit](https://www.streamlit.io/)

- [Turn Python Scripts into Beautiful ML Tools](https://towardsdatascience.com/coding-ml-tools-like-you-code-ml-models-ddba3357eace)

- [github](https://github.com/streamlit/streamlit)

- Get started
```
$ pip install streamlit
$ streamlit hello            # run demo
$ streamlit run [filename]   #  run your script

```

- run a complete neural net (YOLO) in real time
```
$ pip install --upgrade streamlit opencv-python
$ streamlit run https://raw.githubusercontent.com/streamlit/demo-self-driving/master/app.py
```

- How to run streamlit examples
```
$ . ~/projects/streamlit_venv/bin/activate
$ source ~/projects/streamlit_venv/bin/activate

$ cd ~/projects/streamlit/examples

$ streamlit run animation.py
$ streamlit run audio.py
$ streamlit run image.py
$ streamlit run video.py
```


- requirements.txt
streamlit
scipy
wave
plotly
tensorflow
keras


- references

    * https://stackoverflow.com/questions/2229118/is-it-possible-to-play-shoutcast-internet-radio-streams-with-html5

    * https://www.fsf.org/campaigns/playogg/sites/all