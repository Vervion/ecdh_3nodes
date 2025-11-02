# Change Peer addresses to be specific

# Node A listens on 10.0.0.1:5000; it will connect to node B and C
./target/release/rpi-secure-stream --mode=mesh --peer=10.42.0.1:5000 --peer=10.42.0.3:5000 --bind=10.42.0.2:5000 --payload=video --device=libcamera --fps=30 --metrics-dir=metrics/node2
