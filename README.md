
export default function handler(req, res) {
  res.status(200).json({
    success: true,
    status: "ok",
    simulation: true,
    message: "API is running",
    timestamp: new Date().toISOString()
  });
}
