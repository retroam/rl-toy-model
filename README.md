# RL Toy Model

An interactive visual lesson for understanding reinforcement learning through a tiny grid-world agent.

## What it teaches

- Agent, environment, state, action, reward, and policy
- Episodes and exploration versus exploitation
- How a Q-table changes after each transition
- The intuition behind the Q-learning update

## Run locally

```bash
pnpm install
pnpm --filter @workspace/rl-toy-model run dev
```

The app is a client-only React + Vite experience, so the simulation responds instantly without an account or external service.