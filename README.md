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
Packet Transmission Visualization
<img width="395" height="119" alt="image" src="https://github.com/user-attachments/assets/93acd9a3-7490-4a7e-bd75-de5b4c11c8e0" />

The program also prints:

Animation 

The project includes a real-time animation where:
- Packets appear one by one
- Green = Delivered
- Red = Lost
- 
- Animation Preview
  <img width="398" height="350" alt="image" src="https://github.com/user-attachments/assets/70b55fd3-ca8b-42a2-94ee-c2249fc4acf0" />
  <img width="255" height="457" alt="image" src="https://github.com/user-attachments/assets/689565d4-9210-4616-9a59-73c8b0540e68" />
  <img width="256" height="459" alt="image" src="https://github.com/user-attachments/assets/ba9f3c89-1f0b-42e5-a250-70b911363a5e" />
  <img width="255" height="460" alt="image" src="https://github.com/user-attachments/assets/ef5ef134-15b9-4012-9968-7a99dd0b19b7" />
  <img width="255" height="464" alt="image" src="https://github.com/user-attachments/assets/ab3d7ec4-d7ec-483f-993b-37b3429888aa" />
  <img width="253" height="450" alt="image" src="https://github.com/user-attachments/assets/44b7229c-8919-44dd-bcad-05e12a8f2be9" />
  <img width="258" height="455" alt="image" src="https://github.com/user-attachments/assets/b7488cee-ca5d-4cff-b733-d33373700d42" />
  <img width="258" height="460" alt="image" src="https://github.com/user-attachments/assets/747c818d-29d1-4160-9067-f843061946c4" />
  <img width="254" height="450" alt="image" src="https://github.com/user-attachments/assets/4ec9ec57-3c1d-435d-a531-9a5c7f007bd9" />
  <img width="252" height="460" alt="image" src="https://github.com/user-attachments/assets/a5206cda-762d-460f-adfd-9fd04da402dd" />

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
