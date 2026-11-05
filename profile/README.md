```mermaid
graph TD
    subgraph SynAccel ["SynAccel Research Framework"]
        
        subgraph P1 ["01 / Defensive Engineering"]
            Forge["SynAccel-Forge<br/>(Hardened Baselines & Testbeds)"]
            Bridge["SynAccel-Bridge<br/>(Secure Telemetry Pipeline)"]
            Sentinel["SynAccel-Sentinel<br/>(IAM & Infrastructure Isolation)"]
        end

        subgraph P2 ["02 / Adversarial Research"]
            ShieldSet["SynAccel-ShieldSet<br/>(Data Poisoning & Label Audit)"]
            Mirage["SynAccel-Mirage_v2<br/>(Adversary Deception Grid)"]
        end

    end

    ShieldSet --> Bridge
    Mirage --> Bridge
    Bridge --> Sentinel
