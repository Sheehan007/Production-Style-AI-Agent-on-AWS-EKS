# Production-Style-AI-Agent-on-AWS-EKS


**The stack:**

The agent runs inside a Kubernetes-managed container and accesses an external LLM instead of requiring a GPU host for inference.

                 -------------------------------------------------
                 |                  User / Client                |
                 |                REST API Requests              |
                 -------------------------------------------------
                                         |
                 -------------------------------------------------
                 |                AWS Load Balancer              |
                 |              public traffic routing           |
                 -------------------------------------------------
                                         |
                 -------------------------------------------------
                 |             Kubernetes on Amazon EKS          |
                 |        Deploy, recover and scale containers   |
                 -------------------------------------------------
                                         |
                 -------------------------------------------------
                 |           Docker + FastAPI + AI Agent         |
                 |        Python, tools and LLM Orchestration    |
                 -------------------------------------------------
                                         |
                 -------------------------------------------------
                 |             LLM API + Data Services           |
                 |          Model, database, retrieval, tools    |
                 -------------------------------------------------







