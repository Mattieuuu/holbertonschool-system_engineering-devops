# Web Infrastructure Design Project

## Project Overview
This project demonstrates the evolution of web infrastructure design, from a basic single-server setup to a complex, distributed system. Each task builds upon the previous one, introducing new concepts and improvements in reliability, security, and scalability.

## Infrastructure Diagrams
| Task | Description | Link |
|------|-------------|------|
| 0 | Simple Web Stack | [View Diagram](https://imgur.com/a/OINBFBm) |
| 1 | Distributed Web Stack | [View Diagram](https://imgur.com/a/89ocMzm) |
| 2 | Secured & Monitored Stack | [View Diagram](https://imgur.com/a/abmupAK) |
| 3 | Scaled Up Stack | [View Diagram](https://imgur.com/a/KQQ8WIp) |

## Detailed Task Breakdown

### Task 0: Simple Web Stack
**Components:**
- 1 Server (8.8.8.8)
- 1 Web Server (Nginx)
- 1 Application Server
- 1 Application Files
- 1 Database (MySQL)
- 1 Domain Name foobar.com

**Key Concepts Covered:**
- DNS configuration and A records
- HTTP/HTTPS protocols
- Server roles and responsibilities
- Database management
- Single points of failure
- Resource limitations

### Task 1: Distributed Web Infrastructure
**Additional Components:**
- 2 Servers
- 1 Load Balancer (HAproxy)
- Split MySQL Primary-Replica

**Key Features:**
- Load distribution algorithms
- Active-Active vs Active-Passive
- Database replication
- Redundancy implementation
- High availability setup

### Task 2: Secured & Monitored Infrastructure
**Security Additions:**
- 3 Firewalls
- SSL Certificate
- 3 Monitoring Clients

**Security & Monitoring Features:**
- HTTPS/SSL implementation
- Network security
- Performance monitoring
- Data collection
- QPS monitoring
- SSL termination
- Traffic encryption

### Task 3: Scaled Up Infrastructure
**Infrastructure Improvements:**
- Split Components
- Dedicated Servers
- Load Balancer Cluster
- Component Isolation

**Advanced Concepts:**
- Server specialization
- Resource optimization
- Maintenance strategies
- Scalability improvements
- Security isolation

## Technical Requirements

### Server Requirements
- Linux-based operating system
- Web server: Nginx
- Application server capability
- MySQL database server
- Support for monitoring clients

### Network Requirements
- Proper DNS configuration
- Load balancer setup
- Firewall configuration
- SSL/TLS support

### Security Requirements
- Firewall protection
- HTTPS encryption
- Monitoring setup
- Access control
- Network segmentation

## Best Practices Implemented
1. **High Availability**
   - Redundant components
   - Load balancing
   - Failover capabilities

2. **Security**
   - Multi-layer security
   - Encryption
   - Access control
   - Regular monitoring

3. **Scalability**
   - Horizontal scaling
   - Vertical scaling
   - Component isolation
   - Resource optimization

4. **Monitoring**
   - Performance metrics
   - Resource utilization
   - Error tracking
   - System health monitoring

## Common Issues Addressed
1. **Single Points of Failure (SPOF)**
2. **Scalability Limitations**
3. **Security Vulnerabilities**
4. **Maintenance Challenges**
5. **Performance Bottlenecks**

## Tools and Technologies
- **Web Server:** Nginx
- **Database:** MySQL
- **Load Balancer:** HAproxy
- **Monitoring:** Sumologic/Datadog
- **Security:** SSL/TLS, Firewalls
- **Protocol:** HTTP/HTTPS

## Author
Mattieu Mouroux

## License
This project is part of the Holberton School curriculum.

## Additional Resources
- [Nginx Documentation](https://nginx.org/en/docs/)
- [HAProxy Documentation](https://www.haproxy.org/#docs)
- [MySQL Documentation](https://dev.mysql.com/doc/)