# 4x4 Multiplier in Cadence Virtuoso

[Click HERE for project report](./more-info.md)

[Click HERE for project powerpoint recording](./layouts/)

## Full Adder Reference (Textbook Image)
![Full-Adder-Reference](https://github.com/user-attachments/assets/54c2e8d4-6c03-45fa-9ef6-a7209aa6d3b6)

## NxN Array Multiplier Reference (Textbook Image)
![array_multiplier_reference](https://github.com/user-attachments/assets/85f14be7-59e1-49b7-8429-6b27de124c81)

## Final Layout
![final-PROD](https://github.com/user-attachments/assets/5bb6e557-4cbb-482e-b366-54a7577058ed)

### Test Vector Results for 4x4 Bit Multiplier (Normal Mode | TEST = Low)

## **Test Vector 1**  
**Calculation:**  
`(1001)₂ * (1001)₂ = (0101 0001)₂`  
![test_vector_1](https://github.com/user-attachments/assets/1f8d1c16-0e24-4f2c-9e3e-6e7179a9a70f)  
**Explanation:**  
`9₁₀ * 9₁₀ = 81₁₀ = 0101 0001₂`

---

## **Test Vector 2**  
**Calculation:**  
`(1111)₂ * (0011)₂ = (0010 1101)₂`  
![test_vector_2](https://github.com/user-attachments/assets/3bf9e58a-6211-43c3-9d64-6589adaba9fd)  
**Explanation:**  
`15₁₀ * 3₁₀ = 45₁₀ = 0010 1101₂`

---

## **Test Vector 3**  
**Calculation:**  
`(1001)₂ * (1011)₂ = (0110 0011)₂`  
![test_vector_3](https://github.com/user-attachments/assets/7d2a58e3-fcc5-4c4d-b080-ec4796d02da4)  
**Explanation:**  
`9₁₀ * 11₁₀ = 99₁₀ = 0110 0011₂`

---

## **Test Vector 4**  
**Calculation:**  
`(0011)₂ * (0011)₂ = (0000 1001)₂`  
![test_vector_4](https://github.com/user-attachments/assets/f0cd9c77-f66c-460b-9029-d7d697070603)  
**Explanation:**  
`3₁₀ * 3₁₀ = 9₁₀ = 0000 1001₂`

---

## **Test Vector 5**  
**Calculation:**  
`(1111)₂ * (1111)₂ = (1110 0001)₂`  
![test_vector_5](https://github.com/user-attachments/assets/c5ad038d-9463-4e2b-b6a3-1a213810395d)  
**Explanation:**  
`15₁₀ * 15₁₀ = 225₁₀ = 1110 0001₂`

---

## **Test Vector 6**  
**Calculation:**  
`(0000)₂ * (0000)₂ = (0000 0000)₂`  
![test_vector_6](https://github.com/user-attachments/assets/f8d7f08a-c05f-4639-bc83-9256b0bc57e4)  
**Explanation:**  
`0₁₀ * 0₁₀ = 0₁₀ = 0000 0000₂`

---

## **Test Vector 7**  
**Calculation:**  
`(1111)₂ * (0000)₂ = (0000 0000)₂`  
![test_vector_7](https://github.com/user-attachments/assets/274c9a99-3fdb-4b96-967d-bf9803c8d7a5)  
**Explanation:**  
`15₁₀ * 0₁₀ = 0₁₀ = 0000 0000₂`

---

## **Test Vector 8**  
**Calculation:**  
`(1001)₂ * (0011)₂ = (0001 1011)₂`  
![test_vector_8](https://github.com/user-attachments/assets/4b6181b3-7e2c-4b61-b88e-d9d431f1a4c0)  
**Explanation:**  
`9₁₀ * 3₁₀ = 27₁₀ = 0001 1011₂`

---

### Test Mode (TEST=1)

In **Test Mode**, inputs are loaded serially via a **SIPO register**, and outputs are transmitted serially using a **PISO register**.  
This mode is used for debugging and verifying the multiplier's functionality.

### Example:
- **Test Mode = HIGH**:  
  ![testModeHigh](https://github.com/user-attachments/assets/8e855ac0-1821-4862-bd47-d4d3bb789df4)

- **Registers Testing | ALL HIGH**:  
  ![allHighTEST](https://github.com/user-attachments/assets/ff9e8d54-bb89-4395-ad81-12b2abe03d35)

- **Registers Testing | ALL LOW**:  
  ![allLowTEST](https://github.com/user-attachments/assets/9fbe1aee-d42d-403a-8f59-c9d70b582bd4)
