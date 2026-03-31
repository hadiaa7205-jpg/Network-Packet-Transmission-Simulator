Network Packet Transmission Simulator

This project simulates the transmission of network packets in a communication system. Each packet has a probability of being successfully delivered or lost, mimicking real-world network behavior such as congestion, interference, or packet loss.

 Features

- Simulates packet transmission with configurable packet loss probability
- Visualizes delivered vs lost packets using a scatter plot
- Calculates and displays transmission success rate
- Includes optional real-time animation of packet flow

Concept

In real communication systems, not all packets reach their destination successfully. This simulator models that behavior using randomness:

- Each packet is assigned a probability of loss
- Based on this probability, packets are either:
  Delivered
  Lost

This helps in understanding:
- Network reliability
- Packet loss impact
- Basic communication system behavior

---

Technologies Used

- Python
- Matplotlib (for visualization)
- Random module (for simulation)

Project Structure

 How It Works

1. Define total number of packets
2. Set packet loss probability (e.g., 20%)
3. Simulate transmission using random values
4. Separate packets into:
   - Delivered list
   - Lost list
5. Visualize results using scatter plot
6. Calculate success rate

Output Example

- Green dots → Successfully delivered packets  
- Red dots → Lost packets  

The program also prints:

Animation 

The project includes a real-time animation where:
- Packets appear one by one
- Green = Delivered
- Red = Lost

This helps visualize packet flow dynamically.

How to Run

1. Clone this repository: 
2. Open the notebook:
   
3. Run all cells step by step

 Customization

You can modify:

python
num_packets = 20
packet_loss_probability = 0.2
