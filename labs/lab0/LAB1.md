# Lab 1: Network Benchmarking and Cloud Microbenchmarks

## Group Information
- **Group ID:** [Your Group ID]
- **Group Email:** csc26-[group_id]@cit.ac.ug
- **Repository:** [Your GitHub Repo Link]
- **Date Started:** [Date]
- **Date Completed:** [Date]

## Lab Objectives Checklist
- [ ] Launch CloudLab experiment with lab1 profile
- [ ] Run iperf3 between client and server nodes
- [ ] Install DeathStarBench dependencies
- [ ] Deploy hotel reservation application using Docker Swarm
- [ ] Test deployment using curl commands
- [ ] Install and configure wrk2 benchmarking tool
- [ ] Run wrk2 load tests
- [ ] Answer all lab questions
- [ ] Document lessons learned

---

## 1. Experiment Setup

### Experiment Configuration
- **Experiment Name:** `csc26-[group_id]-lab1`
- **Profile:** `csc2202-cloud-project` (lab1 parameter)
- **Nodes:** 2 servers (server0, server1) + 1 client (client0)
- **Cluster:** [Selected cluster name]
- **Start Time:** [Date and Time]
- **Expiration:** [16 hours after start]
- **Created By:** [Member Name]

### Node Information
| Node | SSH Command | IP Address | Status |
|------|-------------|------------|--------|
| server0 | `ssh -A server0-[experiment].cranecloud.cloudlab.us` | [IP] | ✅ Ready |
| server1 | `ssh -A server1-[experiment].cranecloud.cloudlab.us` | [IP] | ✅ Ready |
| client0 | `ssh -A client0-[experiment].cranecloud.cloudlab.us` | [IP] | ✅ Ready |

### SSH Access Verification
```bash
# Verify all nodes are accessible
ssh -A server0 "hostname"
ssh -A server1 "hostname"  
ssh -A client0 "hostname"
