---
title: "1 Two Sum"
date: 2021-02-08T21:55:29+08:00
draft: true
---

```package main

import "fmt"

func twoSum(nums []int, target int) []int {
	for i := 0; i < len(nums); i++ {
		for j := i + 1; j < len(nums); j++ {
			if nums[i]+nums[j] == target {
				return []int{i, j}
			}
		}
	}
	return nil
}

func main() {
	nums := []int{2, 7, 11, 15}
	target := 9
	fmt.Println(nums)
	fmt.Println(twoSum(nums, target))
}
```
