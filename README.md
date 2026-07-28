def calculate_range(numbers):
    return max(numbers) - min(numbers)


if __name__ == "__main__":
    values = [14, 8, 22, 5, 31, 17]

    print(f"Numbers: {values}")
    print(f"Range: {calculate_range(values)}")
