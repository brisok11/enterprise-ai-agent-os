# EnterpriseAI-AgentOS


## Overview

Production-grade multi-agent AI automation platform.


## Features

✓ Multi-Agent Architecture

✓ LangGraph Workflows

✓ RAG Knowledge System

✓ Human-in-the-loop

✓ Enterprise Memory


## Architecture


                 USERS
                   |
                   |
        Web Dashboard / API Clients
                   |
                   |
             FastAPI Gateway
                   |
                   |
        AI Agent Orchestration Layer
              (LangGraph)

                   |
                   
     -----------------------------------
     |                |                |

 Customer Agent   Recruiter Agent   Sales Agent

     |                |                |
     -----------------------------------

                   |
                   
              Tool Layer
              
                   |
    -------------------------------------
    |          |          |             |

   Email      CRM      Database      Search
    API       API        API          API

                   |
              Knowledge Layer

       PostgreSQL + Vector Database

                   |
              LLM Layer

           OpenAI GPT-4/5 API


                   |
             Human Approval
             Review System


## Demo


(video)


## Installation


docker compose up


## API Documentation


## Roadmap


## Author
