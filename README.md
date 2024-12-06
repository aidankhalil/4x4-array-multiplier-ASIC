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
\((1001)_{\text{2}} \times (1001)_{\text{2}} = (0101\ 0001)_{\text{2}}\)
![normal-mode-testVector-1](https://github.com/user-attachments/assets/74d4460e-5eb4-45d0-93cb-da39d95a16b0)
**Explanation:**  
\(9_{10} \times 9_{10} = 81_{10} = 0101\ 0001_{\text{2}}\)

---

## **Test Vector 2**  
**Calculation:**  
\((1111)_{\text{2}} \times (0011)_{\text{2}} = (0010\ 1101)_{\text{2}}\)  
![normal-mode-testVector-2](https://github.com/user-attachments/assets/82861433-5bb8-475a-a6e8-a971568fb9b7)
**Explanation:**  
\(15_{10} \times 3_{10} = 45_{10} = 0010\ 1101_{\text{2}}\)

---

## **Test Vector 3**  
**Calculation:**  
\((1001)_{\text{2}} \times (1011)_{\text{2}} = (0110\ 0011)_{\text{2}}\)  
![normal-mode-testVector-3](https://github.com/user-attachments/assets/4b44891c-9753-49b0-a4a2-dfd3c6a17945)
**Explanation:**  
\(9_{10} \times 11_{10} = 99_{10} = 0110\ 0011_{\text{2}}\)

---

## **Test Vector 4**  
**Calculation:**  
\((0011)_{\text{2}} \times (0011)_{\text{2}} = (0000\ 1001)_{\text{2}}\) 
![normal-mode-testVector-4](https://github.com/user-attachments/assets/62aadbec-374d-477e-a6cc-9cddeeb3f8f2)
**Explanation:**  
\(3_{10} \times 3_{10} = 9_{10} = 0000\ 1001_{\text{2}}\)

---

## **Test Vector 5**  
**Calculation:**  
\((1111)_{\text{2}} \times (1111)_{\text{2}} = (1110\ 0001)_{\text{2}}\)  
![normal-mode-testVector-5](https://github.com/user-attachments/assets/a2046495-2395-4179-847c-537ebf49576e)
**Explanation:**  
\(15_{10} \times 15_{10} = 225_{10} = 1110\ 0001_{\text{2}}\)

---

## **Test Vector 6**  
**Calculation:**  
\((0000)_{\text{2}} \times (0000)_{\text{2}} = (0000\ 0000)_{\text{2}}\)  
![normal-mode-testVector-6](https://github.com/user-attachments/assets/fdf74ee8-6250-4f8a-909a-cd6e4952cbfc)
**Explanation:**  
\(0_{10} \times 0_{10} = 0_{10} = 0000\ 0000_{\text{2}}\)

---

## **Test Vector 7**  
**Calculation:**  
\((1111)_{\text{2}} \times (0000)_{\text{2}} = (0000\ 0000)_{\text{2}}\)  
![normal-mode-testVector-7](https://github.com/user-attachments/assets/1724ef1a-8e9c-42ca-8874-0538f967c0ab)
**Explanation:**  
\(15_{10} \times 0_{10} = 0_{10} = 0000\ 0000_{\text{2}}\)

---

## **Test Vector 8**  
**Calculation:**  
\((1001)_{\text{2}} \times (0011)_{\text{2}} = (0001\ 1011)_{\text{2}}\)  
![normal-mode-testVector-8](https://github.com/user-attachments/assets/409dfbcf-2175-4371-9fcd-70122b742bbb)
**Explanation:**  
\(9_{10} \times 3_{10} = 27_{10} = 0001\ 1011_{\text{2}}\)

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

