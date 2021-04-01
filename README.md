# rtwg_documentation

## On-line documentation link

https://real-time-working-group.readthedocs.io/en/latest/

## Build instructions

```bash
cd ~
git clone https://github.com/ros-realtime/rtwg_documentation
cd rtwg_documentation
docker build -t rtwg_documentation .
docker run -v "$(pwd)":/docs -it rtwg_documentation
```

Build results is located at `~/rtwg_documentation/build/index.html`.
