---
name: react-native-guidelines
description: React Native and Expo best practices for performance, architecture, animations, and platform patterns. Use when building, reviewing, or debugging React Native or Expo apps — FlashList, Reanimated, Gesture Handler, safe areas, mobile performance.
---

# React Native Best Practices

16 rules across 7 sections for Expo/React Native.

## Rules
- Use FlashList instead of FlatList
- React.memo for list items
- Reanimated for all animations (UI thread)
- Gesture Handler over TouchableOpacity
- expo-image instead of Image
- SafeAreaProvider + useSafeAreaInsets
- KeyboardAvoidingView with platform behavior
- Zustand + mmkv for state/persistence
- Monorepo with platform file extensions (.native.tsx)
- Platform.select() not if/else