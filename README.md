# RUL-of-Li-ion-Battery
**Problem Statement:**

Lithium-ion batteries are extensively used in various fields such as consumer electronics, electric vehicles, and space systems due to their high energy density and efficiency. However, these batteries have a finite lifespan. Over time, with repeated charge and discharge cycles, and as the materials within the battery age, the performance deteriorates until the battery no longer functions effectively. Accurately predicting the Remaining Useful Life (RUL) of lithium-ion batteries is crucial to ensuring the reliability and safety of these battery-powered systems.

RUL refers to the period a battery is expected to remain functional before its capacity falls below 70% of its original capacity. This metric, also known as battery cycle life, is pivotal in indicating the battery’s health and performance. As a battery undergoes charge and discharge cycles, its capacity consistently declines due to a predictable degradation trend. When the capacity drops below a specified failure threshold, the battery is deemed unusable. By developing a predictive model for battery life, we can anticipate the RUL, which has a wide array of applications. Understanding RUL is integral to predictive maintenance strategies, as it allows engineers to schedule maintenance, optimize system performance, and prevent unexpected failures.

---

**Scope:**

Lithium-ion batteries are favored in sectors such as transportation, aerospace, and defense because of their high operating voltage, long cycle life, and minimal self-discharge rate. These batteries supply power to electrical systems by storing and releasing electrical energy through internal electrochemical reactions. However, during operation, side reactions can occur, leading to material degradation and capacity loss. This can result in performance decline or even catastrophic failures in electrical systems. Therefore, accurately predicting the RUL of lithium-ion batteries is essential to maintaining the operational reliability and safety of these systems. Effective RUL prediction not only indicates the health of the batteries but also aids in developing maintenance strategies to ensure continued reliability and safety.

---

**Motivation:**

Numerous incidents underscore the importance of RUL prediction to prevent catastrophic outcomes. For example, a Zotye electric vehicle in China spontaneously caught fire on April 11, 2011. Similarly, during a side-impact crash test conducted by the U.S. National Highway Traffic Safety Administration (NHTSA) on May 12, 2011, a GM Volt's battery pack suffered significant damage. Three weeks post-test, the battery temperature spiked, leading to a fire. Another incident occurred in Norway in 2014, where a Tesla Model S caught fire while charging at a fast charging station. Such incidents highlight the critical need for RUL prognostics in lithium-ion batteries to ensure the safety and reliability of vehicles and other battery-powered systems.

---

**Charge and Discharge:**

- **Cathode:** Lithium Metal Oxide
- **Anode:** Graphite
- **Electrolyte:** Lithium salt in an organic solvent

Lithium is a reactive element that is most stable in its metal oxide form. The graphite anode provides a loosely bound structure to store separated Li+ ions. The electrolyte allows only Li+ ions to pass through, preventing electron flow. During charging, an external power source causes the lithium metal oxide to become the positive electrode, while the graphite becomes the negative electrode.

When the external power is applied, electrons flow through the external circuit toward the graphite, while Li+ ions move through the electrolyte to the graphite, charging the cell. This is the most unstable state for Li+ ions. Upon disconnecting the power and connecting a load, Li+ ions and electrons move back to the metal oxide, generating current.  

During this process, electrolytic oxidation occurs at the cathode, degrading cell performance. The reaction between graphite and Li+ ions forms a Solid Electrolyte Interface (SEI), which thickens with each charge-discharge cycle, contributing to battery degradation. During discharge, lithium ions carry the current from the negative to the positive electrode through the non-aqueous electrolyte and separator. In charging, the external power applies an over-voltage, causing Li+ ions to migrate to the negative electrode, embedding into the porous electrode material—a process called intercalation. Energy losses due to contact resistance can account for up to 20% of total energy flow in batteries under typical conditions.
