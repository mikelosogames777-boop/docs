// Así de fácil:
const mind = new MindElixir({
  el: '#mindmap-container',
  data: {
    "nodeData": {
      "topic": "IDEA CENTRAL",
      "children": [
        {
          "topic": "Rama 1",
          "children": [
            {"topic": "Subtema A"},
            {"topic": "Subtema B"}
          ]
        },
        {
          "topic": "Rama 2", 
          "children": [
            {"topic": "Subtema C"}
          ]
        }
      ]
    }
  }
});
mind.init();
