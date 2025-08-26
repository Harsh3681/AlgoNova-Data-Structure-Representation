# com.AlgoNova package

This package contains all Swing panels and supporting classes used by the AlgoNova demo app.

## Adding a new algorithm tab

1. Create a new `JPanel` visualizer class (e.g., `DijkstraVisualizerPanel`) that is self-contained
   and follows the dark theme (see existing panels for reference).
2. Wire it in `Frame.java` by adding:
   ```java
   tabs.addTab("Your Label", new DijkstraVisualizerPanel());
   ```
   Keep labels short and consistent.
3. Prefer local inner models (Node/Edge classes) so you don't accidentally collide with
   other demos.
4. Keep UI controls along the top in a compact bar and use the dark palette:

   ```java
   Color BG = new Color(24,24,26);
   Color SURFACE = new Color(40,40,44);
   Color ACCENT = new Color(70, 80, 200);
   setBackground(BG);
   ```

5. If your panel animates, drive it with `javax.swing.Timer` only (never `java.util.Timer`).

## Project Layout (excerpt)

- `App.java` – entry point (creates `Frame`).
- `Frame.java` – builds the tabbed UI.
- `Stack*` / `Queue*` – existing stack/queue demos.
- `LinkedListVisualizerPanel.java` – modern singly/doubly list visualizer.
- `BSTVisualizerPanel.java` – binary search tree visualizer.
- `BFSVisualizerPanel.java`, `DFSVisualizerPanel.java` – graph traversal visualizers.
