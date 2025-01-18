<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FarmAI Assistant</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.1/font/bootstrap-icons.css" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        .clay-morphism {
            background: rgba(255, 255, 255, 0.7);
            border-radius: 20px;
            box-shadow: 12px 12px 24px rgba(0, 0, 0, 0.1), inset 2px 2px 4px rgba(255, 255, 255, 0.9), inset -2px -2px 4px rgba(0, 0, 0, 0.1);
            backdrop-filter: blur(10px);
        }
        
        body {
            font-family: 'Poppins', sans-serif;
            background: #e6f3ff;
        }
        
        .chat-bubble {
            position: relative;
            margin-bottom: 20px;
            padding: 15px;
            border-radius: 15px;
        }
    </style>
</head>

<body class="min-h-screen p-4 md:p-8">
    <div class="max-w-4xl mx-auto">
        <div class="clay-morphism p-6 md:p-8 mb-8">
            <h1 class="text-3xl md:text-4xl font-bold text-teal-700 mb-4">FarmAI Assistant</h1>
            <p class="text-gray-600 mb-6">Get personalized crop care recommendations based on your farm conditions</p>

            <form id="farmForm" class="space-y-6">
                <div>
                    <label class="block text-gray-700 mb-2">Soil Type</label>
                    <select id="soilType" class="w-full p-3 rounded-lg border border-gray-300 focus:ring-2 focus:ring-teal-500">
                        <option value="">Select soil type</option>
                        <option value="clay">Clay Soil</option>
                        <option value="sandy">Sandy Soil</option>
                        <option value="loam">Loam Soil</option>
                        <option value="silt">Silty Soil</option>
                    </select>
                </div>

                <div>
                    <label class="block text-gray-700 mb-2">Season</label>
                    <select id="season" class="w-full p-3 rounded-lg border border-gray-300 focus:ring-2 focus:ring-teal-500">
                        <option value="">Select season</option>
                        <option value="summer">Summer</option>
                        <option value="winter">Winter</option>
                        <option value="rainy">Rainy</option>
                        <option value="spring">Spring</option>
                    </select>
                </div>

                <div>
                    <label class="block text-gray-700 mb-2">Land Area (in acres)</label>
                    <input type="number" id="landArea" min="0" step="0.1" class="w-full p-3 rounded-lg border border-gray-300 focus:ring-2 focus:ring-teal-500" placeholder="Enter land area">
                </div>

                <div>
                    <label class="block text-gray-700 mb-2">Preferred Crop Type</label>
                    <select id="cropType" class="w-full p-3 rounded-lg border border-gray-300 focus:ring-2 focus:ring-teal-500">
                        <option value="">Select crop type</option>
                        <option value="cereals">Cereals</option>
                        <option value="pulses">Pulses</option>
                        <option value="vegetables">Vegetables</option>
                        <option value="fruits">Fruits</option>
                    </select>
                </div>

                <button type="submit" class="w-full bg-teal-600 text-white py-3 px-6 rounded-lg hover:bg-teal-700 transition duration-300 clay-morphism">
                    Get Recommendations
                </button>
            </form>
        </div>

        <div id="chatContainer" class="clay-morphism p-6 hidden">
            <div id="chatMessages" class="space-y-4 mb-6 max-h-96 overflow-y-auto">
                <!-- Chat messages will appear here -->
            </div>
        </div>
    </div>

    <script>
        const cropData = {
            clay: {
                summer: {
                    cereals: "For clay soil in summer:\n- Recommended crops: Sorghum, Pearl Millet\n- Water requirement: Moderate, every 5-7 days\n- Fertilizer: NPK 14-14-14\n- Best practices: Deep plowing, proper drainage",
                    pulses: "For clay soil in summer:\n- Recommended crops: Black gram, Green gram\n- Water requirement: Low to moderate\n- Fertilizer: DAP based\n- Best practices: Raised bed cultivation",
                    vegetables: "For clay soil in summer:\n- Recommended crops: Okra, Eggplant\n- Water requirement: Regular irrigation\n- Fertilizer: Organic compost + NPK\n- Best practices: Mulching recommended",
                    fruits: "For clay soil in summer:\n- Recommended crops: Pomegranate, Fig\n- Water requirement: Deep watering\n- Fertilizer: Balanced NPK + micronutrients\n- Best practices: Proper spacing"
                },
                // Add more seasons...
            },
            sandy: {
                // Similar structure for sandy soil...
            }
            // Add more soil types...
        };

        document.getElementById('farmForm').addEventListener('submit', function(e) {
            e.preventDefault();
            const soilType = document.getElementById('soilType').value;
            const season = document.getElementById('season').value;
            const landArea = document.getElementById('landArea').value;
            const cropType = document.getElementById('cropType').value;

            if (!soilType || !season || !landArea || !cropType) {
                alert('Please fill all fields');
                return;
            }

            // Show chat container
            document.getElementById('chatContainer').classList.remove('hidden');

            // Add user message
            addMessage(I have $ {
                    landArea
                }
                acres of $ {
                    soilType
                }
                soil and want to grow $ {
                    cropType
                } in $ {
                    season
                }
                season., 'user');

            // Generate and add AI response
            const recommendation = generateRecommendation(soilType, season, landArea, cropType);
            setTimeout(() => {
                addMessage(recommendation, 'ai');
            }, 1000);
        });

        function addMessage(text, sender) {
            const chatMessages = document.getElementById('chatMessages');
            const messageDiv = document.createElement('div');
            messageDiv.className = chat - bubble clay - morphism $ {
                sender === 'user' ? 'bg-teal-50 ml-12' : 'bg-white mr-12'
            };
            messageDiv.innerHTML = `
                <div class="flex items-start">
                    <i class="bi ${sender === 'user' ? 'bi-person-circle' : 'bi-robot'} text-2xl ${sender === 'user' ? 'text-teal-600' : 'text-blue-600'} mr-2"></i>
                    <div class="flex-1">
                        <div class="font-medium ${sender === 'user' ? 'text-teal-600' : 'text-blue-600'} mb-1">
                            ${sender === 'user' ? 'You' : 'FarmAI'}
                        </div>
                        <div class="text-gray-700 whitespace-pre-line">${text}</div>
                    </div>
                </div>`;
            chatMessages.appendChild(messageDiv);
            chatMessages.scrollTop = chatMessages.scrollHeight;
        }

        function generateRecommendation(soilType, season, landArea, cropType) {
            try {
                let recommendation = cropData[soilType][season][cropType];
                if (!recommendation) {
                    return `Based on your inputs, I recommend:\n
                    1. For ${soilType} soil in ${season}:
                    - Ensure proper soil preparation
                    - Maintain adequate drainage
                    - Regular soil testing
                    
                    2. For ${landArea} acres:
                    - Consider crop rotation
                    - Implement irrigation system
                    - Plan for proper resource allocation
                    
                    3. General care tips:
                    - Monitor soil moisture regularly
                    - Watch for pest infestations
                    - Follow local agricultural guidelines`;
                }
                return recommendation;
            } catch (error) {
                return `I recommend consulting with a local agricultural expert for detailed guidance specific to your conditions. However, here are some general tips:\n
                1. Soil Management:
                - Regular testing
                - Proper drainage
                - Organic matter addition
                
                2. Water Management:
                - Install efficient irrigation
                - Monitor moisture levels
                - Avoid waterlogging
                
                3. Crop Protection:
                - Regular monitoring
                - Integrated pest management
                - Proper spacing`;
            }
        }
    </script>
</body>

</html>
